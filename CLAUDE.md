# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

# GymBuddy – Projektkontext

Wissenschaftsbasierte Krafttraining-App für Jan (Berufskolleg-Lehrer) und eine kleine Gruppe ausgewählter Nutzer. Gehostet auf GitHub Pages.

## Architektur – nicht verhandelbar

- **Eine einzige, selbstenthaltene HTML-Datei**: im Repo `index.html` (GitHub Pages liefert sie aus; Jan lädt lokal oft eine `gym-buddy.html`/`gym-buddy-v2.html` hoch → Inhalt 1:1 nach `index.html` übernehmen). Sonst liegt nichts im Repo. Kein Build-Schritt, kein Bundler, kein npm-Projekt zur Laufzeit.
- CSS und JavaScript **inline** in derselben Datei. Keine externen `<script src>`/`<link>` außer Google Fonts (Anton, Hanken Grotesk, JetBrains Mono).
- Einzige externe Laufzeit-Abhängigkeit: Übungsbilder von `raw.githubusercontent.com/yuhonas/free-exercise-db` (kostenlos, kein Schlüssel, Public Domain). Keine weiteren APIs, keine Schlüssel im Code (Sicherheitsrisiko bei einer öffentlichen Datei – jeder Schlüssel im Quelltext ist für jeden Besucher einsehbar).
- Daten liegen ausschließlich in `localStorage` des Nutzers (Präfix `tpe.`), nichts läuft über einen eigenen Server.
- Demo-Datei `gym-buddy-demo.html`: **nur auf ausdrückliche Bitte erstellen**, nicht automatisch bei jeder Änderung.

## Deployment

- Änderung an `index.html` → Commit auf Arbeitszweig → nach `main` pushen (Jan wünscht direkte Übernahme in `main`, kein PR) → GitHub Pages baut automatisch neu, URL bleibt gleich.
- **Cache-Busting ist Pflicht**: Bei jeder Auslieferung die Versionsnummer in der Aufruf-URL hochzählen (`?N` anhängen/erhöhen), sonst lädt das Handy die alte gecachte Version.
- localStorage-Daten der Nutzer bleiben bei jedem Update erhalten (kein Reset).

## Befehle (kein Build, kein package.json)

```bash
# Syntax: Inline-Script extrahieren und prüfen
python3 -c "import re;s=open('index.html',encoding='utf-8').read();open('/tmp/x.js','w').write('\n;\n'.join(re.findall(r'<script(?![^>]*src)[^>]*>(.*?)</script>',s,re.S)))" && node --check /tmp/x.js
# Playwright ist global installiert → als CommonJS-Skript (.cjs) ausführen:
NODE_PATH=$(npm root -g) node test.cjs
#   chromium.launch({executablePath:'/opt/pw-browsers/chromium'}), page.goto('file:///…/index.html'),
#   Testdaten per page.addInitScript in localStorage legen, dann Funktionen per page.evaluate aufrufen
#   (z. B. makePlan(); startWorkout(0); showView('hist'); renderTrain(); finishWorkout()).
```

Hinweis Sandbox: Google Fonts laden im Test ggf. nicht → Screenshots zeigen Ersatzschriften (breiter als Anton); Layout-Überläufe daher mit Vorsicht bewerten.

## Teststrategie vor jeder Auslieferung

1. **Syntax**: `<script>`-Inhalt extrahieren, `node --check` darauf laufen lassen.
2. **Laufzeit-Logik**: Node + jsdom, `localStorage` mit realistischen Testdaten vorbelegen (Konfiguration, Log-Einträge – **immer neueste-zuerst-Reihenfolge**, wie `finishWorkout()` es per `unshift` tatsächlich speichert – ein häufiger Test-Stolperstein), dann Funktionen direkt aufrufen und Zustände prüfen.
3. **Visuell**: Playwright, mobiler Viewport 390×844, Screenshots der betroffenen Ansichten vor der Auslieferung ansehen.
4. Bei Bugfixes: den ursprünglichen Fehler zuerst reproduzieren, dann den Fix verifizieren, dann eine kleine Regressionsprüfung angrenzender Funktionen.
5. Erst nach bestandenen Tests ausliefern.

## Aufbau von `index.html` (~2900 Zeilen)

- **CSS in Schichten**: Basis-Styles oben, darunter Block `/* REDESIGN 2026 · Logbuch-Look */`, der frühere Regeln per Kaskade **überschreibt** (z. B. `.navbar`, `.cat-search`, `:root`-Farben), danach `/* Redesign · Übungen & Fortschritt */`. Vor dem Ändern einer Regel immer nach allen Vorkommen des Selektors greppen – die letzte gewinnt.
- **HTML**: vier Ansichten `section.view#v-plan|v-train|v-hist|v-cat` mit Container `#…-out`, Umschalten per `showView(v)`; Desktop-Tabs `.tabs` + mobile `nav.navbar` (unter 761px). Modals als `.modal-bg`.
- **JS** (ein `<script>` am Ende, Abschnitte mit `// ============ NAME ============`): STORAGE (`jget`/`jset`) → DATA (`EX` Übungskatalog mit `n,pat,eq,lvl,t,pri,sec[,tm]`; `MUS`, `EQL`, `MORDER`, `LM` = MEV/MRV je Muskel) → GENERATE/ANALYSIS (Planerzeugung, Volumen) → RENDER: PLAN → TRAINING (`logState`, `renderTrain`, `finishWorkout`) → TIMER → HISTORY (`renderHist`, `drawE1`, `areaChart`, DOTS) → EXERCISE CATALOG (`renderCatalog`, `catCardHTML`, `renderCatDetail`) → CONTROLS/VIEWS.
- **Rendering**: jede Ansicht baut per Template-String einen HTML-String und setzt `innerHTML`; Events über Inline-`onclick`. Kein Framework, kein virtuelles DOM.
- **localStorage-Schlüssel** (`tpe.`): `log` (Einheiten, neueste zuerst), `e1rm`/`repbest`/`tmbest` (Bestwerte je Übung), `plan`, `cfg`, `customplans`, `fav`, `excl`, `draft` (laufendes Workout), `theme`/`colortheme`, `histP` (Zeitraum Fortschritt), `audiocue`, `ui`, `username`, `lastBackup`. Formate nie inkompatibel ändern – Nutzerdaten müssen Updates überleben.
- Log-Eintrag: `{id,date(ISO),week,di,dayLabel,entries:[{name,sets:[{w(kg),r,rir?}]}],totalSets,durationSec,goal}`; Gewichte intern immer kg, Anzeige über `showW`/`fromKg`/`unitLbl` (kg/lbs).
- iOS-Tastatur: Bei Fokus auf Eingabefeldern bekommt `body` die Klasse `kb`, die `.navbar` ausblendet (sonst schiebt iOS die fixierte Leiste über die Tastatur).

## Design-Vorlage

Jans Redesign-Entwürfe liegen im claude.ai-Artefakt „Gym Buddy Redesign“ (Design-Canvas, Artboards Main/Workout/Done/Progress/Exercises + Dark-Varianten, je 390×844). Bei Designfragen dort abgleichen (Artifact-Tool `read`). Typografie-Regel daraus: Anton für Titel/große Zahlen, Hanken Grotesk für Text, JetBrains Mono (`var(--mono)`) für kleine Zahlen-/Datenlabels.

## Code-Stil

- Sehr dichter, kompakter JS/CSS-Stil (keine Formatierungs-Whitespace-Verschwendung, Datei bleibt eine einzelne Datei unter vernünftiger Größe).
- CSS über Custom Properties (`--accent`, `--bg`, `--ink` usw.) in `:root` (hell) und `html.dark` (dunkel) sowie `html[data-theme="X"]` für zusätzliche Farbschemata (Orange/Petrol/Rosé/Kobalt).
- Schriften: **Anton** (Überschriften/große Zahlen), **Hanken Grotesk** (Fließtext), **JetBrains Mono** (kleine Daten-/Zahlenlabels).
- Akzentfarbe Orange (seit Redesign `--accent:#D63A14`, vorher `#E8431D`), sportlich-reduziertes Design.
- UI-Sprache: Deutsch, durchgehend.

## Kommunikationsstil (für Antworten an Jan)

- Deutsch, prägnant, keine unnötige Präambel.
- Bei wissenschaftlichen/Design-Fragen: fundierte Einordnung mit Quellenbezug, ggf. echte Websuche für aktuelle Studienlage statt aus dem Gedächtnis behaupten.
- Bei größeren architektonischen Änderungen: kurz Vorgehen vorschlagen und bestätigen lassen, bevor umgesetzt wird – nicht bei kleinen, klar umrissenen Bitten.
- Nach jeder Auslieferung: Cache-Bust-Hinweis, Bestätigung „Daten bleiben erhalten".

## Aktueller funktionaler Stand (Kurzüberblick)

- **Trainingsplan**: Wird **wochenweise** erzeugt (kein fixer Mehrwochen-Block mehr, keine Wochenauswahl, kein Deload-Konzept). Sätze: Grundübungen 4, Isolationsübungen 3 (nie mehr, feste Werte aus `SCHEME`). Fortschritt läuft über Autoregulation: Gewichtsvorschlag folgt dem tatsächlichen Ergebnis der letzten Einheit (Ziel-Wdh + RIR erreicht → Last steigern, sonst Gewicht halten), nicht über eine vorausberechnete Kurve.
- **Splits**: Automatisch, Ganzkörper, Ober/Unter, Push/Pull/Beine, sowie „Brust+Rücken / Schultern+Arme / Beine" (Arnold-Split-Variante).
- **Übungskatalog**: 125 Übungen, nach Muskelgruppe gruppiert, mit Bildern, Favoriten- und Sperrliste-Funktion.
- **Workout-Logging**: Satz-Eingabe mit Gewicht/Wdh/RIR, Übungstausch, Timer mit Sprachansage (30s/15s/„Los geht's", Erstnutzung braucht einmaliges „Aufwecken" der Sprachausgabe per Nutzer-Tap), PR-Erkennung, Konfetti-Feier-Fenster nach Abschluss.
- **Eigene Pläne**: Baukasten zum manuellen Zusammenstellen, speicherbar unter eigenem Namen, jederzeit spontan startbar (wie „Spontanes Training"), Teilen per Link (Base64 in URL) oder – sicherer, umgeht Safari/installierte-App-Speichertrennung auf iOS – per Datei-Export/Import. Teilen überträgt **nur** die Planstruktur, nie Trainingsdaten.
- **Fortschritt**: Zeitraum 4 W/12 W/Jahr, Kennzahlen (Einheiten/Serie/Tonnage), Bestleistungen-Liste, Balance Druck:Zug und Quad:Beinbeuger, e1RM-Kurven (RIR-Vertrauensanzeige: volle vs. hohle Punkte), DOTS-Score, Muskelmännchen-Visualisierung, druckbarer PDF-Fortschrittsbericht (über `window.print()`, kein PDF-Build nötig).
- **Wissenschaftliche Grundlage**: NSCA-Belastungskontinuum, MEV/MRV-Volumen-Landmarks (Israetel/RP), ACSM-2026-Position (Konsistenz vor Komplexität, ≥2×/Woche Frequenz, ~10 Sätze/Muskel/Woche für Hypertrophie, Periodisierung nicht zwingend nötig).

## Bekannte Plattform-Grenzen (nicht erneut versuchen zu lösen)

- Kein Sperrbildschirm-Countdown möglich (iOS erlaubt das Web-Apps nicht).
- Sprachausgabe/Audio pausiert bei gesperrtem Bildschirm (harte iOS-Grenze).
- Safari und eine als „Zum Home-Bildschirm hinzufügen" installierte Web-App haben auf iOS getrennten `localStorage` – deshalb der dateibasierte Plan-Import als verlässlicher Umweg.
