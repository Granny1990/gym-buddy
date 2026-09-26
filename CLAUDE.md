# GymBuddy – Projektkontext für Claude Code

Wissenschaftsbasierte Krafttraining-App für Jan (Berufskolleg-Lehrer) und eine kleine Gruppe ausgewählter Nutzer. Gehostet auf GitHub Pages.

## Architektur – nicht verhandelbar

- **Eine einzige, selbstenthaltene HTML-Datei**: `gym-buddy.html`. Kein Build-Schritt, kein Bundler, kein npm-Projekt zur Laufzeit.
- CSS und JavaScript **inline** in derselben Datei. Keine externen `<script src>`/`<link>` außer Google Fonts (Anton + Hanken Grotesk).
- Einzige externe Laufzeit-Abhängigkeit: Übungsbilder von `raw.githubusercontent.com/yuhonas/free-exercise-db` (kostenlos, kein Schlüssel, Public Domain). Keine weiteren APIs, keine Schlüssel im Code (Sicherheitsrisiko bei einer öffentlichen Datei – jeder Schlüssel im Quelltext ist für jeden Besucher einsehbar).
- Daten liegen ausschließlich in `localStorage` des Nutzers (Präfix `tpe.`), nichts läuft über einen eigenen Server.
- Demo-Datei `gym-buddy-demo.html`: **nur auf ausdrückliche Bitte erstellen**, nicht automatisch bei jeder Änderung.

## Deployment

- Änderung an `gym-buddy.html` vornehmen → dieselbe Datei im GitHub-Repo ersetzen (gleicher Dateiname) → GitHub Pages baut automatisch neu, URL bleibt gleich.
- **Cache-Busting ist Pflicht**: Bei jeder Auslieferung die Versionsnummer in der Aufruf-URL hochzählen (`?N` anhängen/erhöhen), sonst lädt das Handy die alte gecachte Version.
- localStorage-Daten der Nutzer bleiben bei jedem Update erhalten (kein Reset).

## Teststrategie vor jeder Auslieferung

1. **Syntax**: `<script>`-Inhalt extrahieren, `node --check` darauf laufen lassen.
2. **Laufzeit-Logik**: Node + jsdom, `localStorage` mit realistischen Testdaten vorbelegen (Konfiguration, Log-Einträge – **immer neueste-zuerst-Reihenfolge**, wie `finishWorkout()` es per `unshift` tatsächlich speichert – ein häufiger Test-Stolperstein), dann Funktionen direkt aufrufen und Zustände prüfen.
3. **Visuell**: Playwright, mobiler Viewport 390×844, Screenshots der betroffenen Ansichten vor der Auslieferung ansehen.
4. Bei Bugfixes: den ursprünglichen Fehler zuerst reproduzieren, dann den Fix verifizieren, dann eine kleine Regressionsprüfung angrenzender Funktionen.
5. Erst nach bestandenen Tests ausliefern.

## Code-Stil

- Sehr dichter, kompakter JS/CSS-Stil (keine Formatierungs-Whitespace-Verschwendung, Datei bleibt eine einzelne Datei unter vernünftiger Größe).
- CSS über Custom Properties (`--accent`, `--bg`, `--ink` usw.) in `:root` (hell) und `html.dark` (dunkel) sowie `html[data-theme="X"]` für zusätzliche Farbschemata (Orange/Petrol/Rosé/Kobalt).
- Schriften: **Anton** (Überschriften/Zahlen), **Hanken Grotesk** (Fließtext).
- Akzentfarbe Orange (`#E8431D`), sportlich-reduziertes Design.
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
- **Fortschritt**: e1RM-Kurven (RIR-Vertrauensanzeige: volle vs. hohle Punkte), DOTS-Score, Muskelmännchen-Visualisierung, druckbarer PDF-Fortschrittsbericht (über `window.print()`, kein PDF-Build nötig).
- **Wissenschaftliche Grundlage**: NSCA-Belastungskontinuum, MEV/MRV-Volumen-Landmarks (Israetel/RP), ACSM-2026-Position (Konsistenz vor Komplexität, ≥2×/Woche Frequenz, ~10 Sätze/Muskel/Woche für Hypertrophie, Periodisierung nicht zwingend nötig).

## Bekannte Plattform-Grenzen (nicht erneut versuchen zu lösen)

- Kein Sperrbildschirm-Countdown möglich (iOS erlaubt das Web-Apps nicht).
- Sprachausgabe/Audio pausiert bei gesperrtem Bildschirm (harte iOS-Grenze).
- Safari und eine als „Zum Home-Bildschirm hinzufügen" installierte Web-App haben auf iOS getrennten `localStorage` – deshalb der dateibasierte Plan-Import als verlässlicher Umweg.
