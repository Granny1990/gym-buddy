<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
<meta name="mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="default">
<meta name="apple-mobile-web-app-title" content="Training">
<meta name="theme-color" content="#E8431D">
<link rel="icon" href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAgAAAAIACAIAAAB7GkOtAAAABmJLR0QA/wD/AP+gvaeTAAAMP0lEQVR4nO3dT4ic9R3H8ed5dna3mewmNtZI1iRrC/VUK24vAVtPKrRQkV7Eg5VCTz2p0N5ESk+ltKUggr2UVhDx0Ir0H0ppCXgy6lkoxJhoiakm2Swr2dl5nh7rrOuimZnMPPN5vc7Jw499ft99P88zyzzlysrNBQB5qkkvAIDJEACAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACE6kx6ATPlxP7q3gPVWrc63Cn2fea2btTNe73i1Sv1S5frM1vNOBcIE2ZGpkq5snLzpNcwC1YXyieOdNa65TAH2W6K5y72n36/b4cze8zIFJpbXl6a9Bpab61bPrM6f+vCUDu7KIqqLO7YV611y39eaexvZokZmU4CMKzVhfKZ1fnl0X2YcmS+/Hq3+tt6XY/skDBJZmRqCcCwfnl0BNc1O6zMl01RnNp0hcMsMCNTy18BDeXE/mrIZ5qf5pEb5w77hJ72MyPTTACGct+Bcf0AF8vigRvmxnRwuG7MyDQTgKHc2R3jD/DuJWeH1jMj08yPbyg3jfMO9NjiGA8O14cZmWYCMJRxXtwUy9VYnpzC9WRGppkAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFC+TbXdDnWKhw7NfXN/dXyh3PsNqxt1c/pq8dfL/T9eqnu+RJ1PsJcCCUCL3bNcPbnS2f/Z7uKWqvL2fcXt+zoPfrF5/N3tt68aXP7PXsrkEVBb3bNc/fzoZ53Yj7t1sfzd6vzxUb+hifayl2IJQCsd6hRPrnSueewOzhW/ONq59v/PDLGXkglAKz10aO4artc+7quL5XfG9qomWsReSua0tdK3RvEipO96nR72UjYBaKWj8yO45b7tC8Mfg9azl5IJQCuN5C1L3qZEYS9lEwCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAqM6kF8BUO7G/uvdAtdatDneKfa4WWmKjbt7rFa9eqV+6XJ/Zaia9HKaXALC71YXyiSOdtW456YXwuS1V5W2LxW2Lcw/fOPfcxf7T7/dVgF25qGMXa93yD1+e99u/7Tpl8f1Dc08f7yxXTiW7EAB2Wl0of31sftnWmBVr3epXxzodCeATTDk7PXGk47f/jPlGt/zhl+YmvQqmjkFnwIn9lSc/M+mRG+cO+8iPQQLAgPsO2BKzabEsHrjBTQADTDsD7uzaEjPr7iUnlwE2BANu8pRgdh1bnPQKmDICwAA3ADPMH4Oyg3EHCCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAM2Ki9O2pmbfSdXAYIAAPObk16BYzNhe1Jr4ApIwAMOLlRT3oJjMvrm04uAwSAAS9e6l/1nGBGvbLu1DJAABhwvlc8+0F/0qtg9E5tNq+5A2CQALDTb//bf33TpeJMWe8XP3vPJwDsJADstN0Uj5/dfkMDZsV6v3jsXO9szwllJwFgF1fq5kfv9H7/Qb1d+K3Rbqc2m4dP996Uc3bjBYDsbqspfvP+9p8ulfcfrO5aqm5ZKJa8T6olNuvifK95Y7N+ed1zf/YiAOzlna3mqQv9py74WBhmkEdAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFAC0EobdTOCg/RHcBDazl5KJgCt9NZHIzjIuZ6hxV6KJgCt9Jf1/vAHOblhaLGXoglAK/35cv3vq0ON3EbdPP/hCCaftrOXkglAK203xY/PbV++1qFriuKn/+lfMrPYS9kEoK3ObDU/ONM7/fmv3Tbq5ifvbv9jvR7HqmgjeylWZ9IL4Nq9fbV58HTvezdU3z5YfWWxXK7KPf7xZl28s9Wc3Kif/9D1GjvZS5kEoN22m+KFi/ULF12CMSx7KZBHQAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAAxlJG9T+tSDe8sS7WdGppkADOXs1hgPfmF7jAeH68OMTDMBGMrJjTF+c9brm76Wi9YzI9NMAIby4qX+cC9T2ssr625vaT0zMs0EYCjne8WzH4zlC9FPbTavubqh/czINJtbXl6a9Bra7c2PmrVutTK/1ws0Pq/1fvHo2W3vWWI2mJGpJQDDqoviX1eaO7rVkRHt7/V+8di53lvju22G68uMTC0BGIGtpvj7ej1fll/rFlUx1BY/tdk8enbbzmbGmJHpVK6s3DzpNcyO4wvl/Qeru5aqWxaKpT3fqvpxm3Vxvte8sVm/vO6ZJjPOjEwVAQAI5a+AAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEL9D7tpU318LTgQAAAAAElFTkSuQmCC">
<link rel="apple-touch-icon" href="data:image/png;base64,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AAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEIJAEAoAQAIJQAAoQQAIJQAAIQSAIBQAgAQSgAAQgkAQCgBAAglAAChBAAglAAAhBIAgFACABBKAABCCQBAKAEACCUAAKEEACCUAACEEgCAUAIAEEoAAEL9D7tpU318LTgQAAAAAElFTkSuQmCC">
<link rel="manifest" href="data:application/manifest+json;base64,eyJuYW1lIjogIlRyYWluaW5ncy1FbmdpbmUiLCAic2hvcnRfbmFtZSI6ICJUcmFpbmluZyIsICJzdGFydF91cmwiOiAiLiIsICJkaXNwbGF5IjogInN0YW5kYWxvbmUiLCAib3JpZW50YXRpb24iOiAicG9ydHJhaXQtcHJpbWFyeSIsICJiYWNrZ3JvdW5kX2NvbG9yIjogIiNFRUVCRTMiLCAidGhlbWVfY29sb3IiOiAiI0U4NDMxRCIsICJpY29ucyI6IFt7InNyYyI6ICJkYXRhOmltYWdlL3BuZztiYXNlNjQsaVZCT1J3MEtHZ29BQUFBTlNVaEVVZ0FBQWdBQUFBSUFDQUlBQUFCN0drT3RBQUFBQm1KTFIwUUEvd0QvQVArZ3ZhZVRBQUFNUDBsRVFWUjRuTzNkVDRpYzlSM0g4ZWQ1ZG5hM21ld21OdFpJMWlSckMvVlVLMjR2QVZ0UEtyUlFrVjdFZzVWQ1R6MnAwTjVFU2srbHRLVWdncjJVVmhEeDBJcjBIMHBwQ1hneTZsa294SmhvaWFrbTJTd3IyZGw1bmg3cnJPdWltWm5NUFBONXZjN0p3NDk5ZnQ5OVA4OHp5enpseXNyTkJRQjVxa2t2QUlESkVBQ0FVQUlBRUVvQUFFSUpBRUFvQVFBSUpRQUFvUVFBSUpRQUFJUVNBSUJRQWdBUVNnQUFRZ2tBUUNnQkFBZ2xBQUNoQkFBZ2xBQUFoQklBZ0ZBQ0FCQktBQUJDQ1FCQUtBRUFDQ1VBQUtFRUFDQ1VBQUNFRWdDQVVBSUFFRW9BQUVJSkFFQW9BUUFJSlFBQW9RUUFJSlFBQUlRU0FJQlFBZ0FRU2dBQVFna0FRQ2dCQUFnbEFBQ2hCQUFnbEFBQWhCSUFnRkFDQUJCS0FBQkNDUUJBS0FFQUNDVUFBS0VFQUNDVUFBQ0VFZ0NBVUFJQUVFb0FBRUlKQUVBb0FRQUlKUUFBb1FRQUlKUUFBSVFTQUlCUUFnQVFTZ0FBUWdrQVFDZ0JBQWdsQUFDaEJBQWdsQUFBaEJJQWdGQUNBQkJLQUFCQ0NRQkFLQUVBQ0NVQUFLRUVBQ0NVQUFDRUVnQ0FVQUlBRUVvQUFFSUpBRUFvQVFBSUpRQUFvUVFBSUpRQUFJUVNBSUJRQWdBUVNnQUFRZ2tBUUNnQkFBZ2xBQUNoQkFBZ2xBQUFoQklBZ0ZBQ0FCQktBQUJDQ1FCQUtBRUFDQ1VBQUtFRUFDQ1VBQUNFRWdDQVVBSUFFRW9BQUVJSkFFQW9BUUFJSlFBQW9RUUFJSlFBQUlRU0FJQlFBZ0FRU2dBQVFna0FRQ2dCQUFnbEFBQ2hCQUFnbEFBQWhCSUFnRkFDQUJCS0FBQkNDUUJBS0FFQUNDVUFBS0VFQUNDVUFBQ0VFZ0NBVUFJQUVFb0FBRUlKQUVBb0FRQUlKUUFBb1FRQUlKUUFBSVFTQUlCUUFnQVFTZ0FBUWdrQVFDZ0JBQWdsQUFDaEJBQWdsQUFBaEJJQWdGQUNBQkJLQUFCQ0NRQkFLQUVBQ0NVQUFLRUVBQ0NVQUFDRUVnQ0FVQUlBRUVvQUFFSUpBRUFvQVFBSUpRQUFvUVFBSUpRQUFJUVNBSUJRQWdBUVNnQUFRZ2tBUUNnQkFBZ2xBQUNoQkFBZ2xBQUFoQklBZ0ZBQ0FCQktBQUJDQ1FCQUtBRUFDQ1VBQUtFRUFDQ1VBQUNFRWdDQVVBSUFFRW9BQUVJSkFFQW9BUUFJSlFBQW9RUUFJSlFBQUlRU0FJQlFBZ0FRU2dBQVFna0FRQ2dCQUFnbEFBQ2hCQUFnbEFBQWhCSUFnRkFDQUJCS0FBQkNDUUJBS0FFQUNDVUFBS0VFQUNDVUFBQ0U2a3g2QVRQbHhQN3EzZ1BWV3JjNjNDbjJmZWEyYnRUTmU3M2kxU3YxUzVmck0xdk5PQmNJRTJaR3BrcTVzbkx6cE5jd0MxWVh5aWVPZE5hNjVUQUgyVzZLNXk3Mm4zNi9iNGN6ZTh6SUZKcGJYbDZhOUJwYWI2MWJQck02Zit2Q1VEdTdLSXFxTE83WVY2MTF5MzllYWV4dlpva1ptVTRDTUt6VmhmS1oxZm5sMFgyWWNtUysvSHEzK3R0NlhZL3NrREJKWm1ScUNjQ3dmbmwwQk5jMU82ek1sMDFSbk5wMGhjTXNNQ05UeTE4QkRlWEUvbXJJWjVxZjVwRWI1dzc3aEo3Mk15UFRUQUNHY3QrQmNmMEFGOHZpZ1J2bXhuUnd1RzdNeURRVGdLSGMyUjNqRC9EdUpXZUgxak1qMDh5UGJ5ZzNqZk1POU5qaUdBOE8xNGNabVdZQ01KUnhYdHdVeTlWWW5wekM5V1JHcHBrQUFJUVNBSUJRQWdBUVNnQUFRZ2tBUUNnQkFBZ2xBQUNoQkFBZ2xBQUFoQklBZ0ZDK1RiWGREbldLaHc3TmZYTi9kWHloM1BzTnF4dDFjL3BxOGRmTC9UOWVxbnUrUkoxUHNKY0NDVUNMM2JOY1BiblMyZi9aN3VLV3F2TDJmY1h0K3pvUGZyRjUvTjN0dDY4YVhQN1BYc3JrRVZCYjNiTmMvZnpvWjUzWWo3dDFzZnpkNnZ6eFViK2hpZmF5bDJJSlFDc2Q2aFJQcm5TdWVld096aFcvT05xNTl2L1BETEdYa2dsQUt6MTBhTzRhcnRjKzdxdUw1WGZHOXFvbVdzUmVTdWEwdGRLM1J2RWlwTzk2blI3MlVqWUJhS1dqOHlPNDViN3RDOE1mZzlhemw1SUpRQ3VONUMxTDNxWkVZUzlsRXdDQVVBSUFFRW9BQUVJSkFFQW9BUUFJSlFBQW9RUUFJSlFBQUlRU0FJQlFBZ0FRU2dBQVFna0FRQ2dCQUFnbEFBQ2hCQUFnbEFBQWhCSUFnRkFDQUJCS0FBQkNDUUJBcU02a0Y4QlVPN0cvdXZkQXRkYXREbmVLZmE0V1dtS2pidDdyRmE5ZXFWKzZYSi9aYWlhOUhLYVhBTEM3MVlYeWlTT2R0VzQ1NllYd3VTMVY1VzJMeFcyTGN3L2ZPUGZjeGY3VDcvZFZnRjI1cUdNWGE5M3lEMStlOTl1LzdUcGw4ZjFEYzA4Zjd5eFhUaVc3RUFCMldsMG9mMzFzZnRuV21CVnIzZXBYeHpvZENlQVRURGs3UFhHazQ3Zi9qUGxHdC96aGwrWW12UXFtamtGbndJbjlsU2MvTSttUkcrY08rOGlQUVFMQWdQc08yQkt6YWJFc0hyakJUUUFEVERzRDd1emFFalByN2lVbmx3RTJCQU51OHBSZ2RoMWJuUFFLbURJQ3dBQTNBRFBNSDRPeWczRUhDQ1VBQUtFRUFDQ1VBQUNFRWdDQVVBSUFFRW9BQUVJSkFFQW9BUUFJSlFBTTJLaTlPMnBtYmZTZFhBWUlBQVBPYmsxNkJZek5oZTFKcjRBcEl3QU1PTGxSVDNvSmpNdnJtMDR1QXdTQUFTOWU2bC8xbkdCR3ZiTHUxREpBQUJod3ZsYzgrMEYvMHF0ZzlFNXROcSs1QTJDUUFMRFRiLy9iZjMzVHBlSk1XZThYUDN2UEp3RHNKQURzdE4wVWo1L2Rma01EWnNWNnYzanNYTzlzendsbEp3RmdGMWZxNWtmdjlINy9RYjFkK0szUmJxYzJtNGRQOTk2VWMzYmpCWURzYnFzcGZ2UCs5cDh1bGZjZnJPNWFxbTVaS0phOFQ2b2xOdXZpZks5NVk3TitlZDF6Zi9ZaUFPemxuYTNtcVF2OXB5NzRXQmhta0VkQUFLRUVBQ0NVQUFDRUVnQ0FVQUlBRUVvQUFFSUpBRUFvQVFBSUpRQUFvUVFBSUpRQUFJUVNBSUJRQWdBUVNnQUFRZ2tBUUNnQkFBZ2xBQUNoQkFBZ2xBQUFoQklBZ0ZBQzBFb2JkVE9DZy9SSGNCRGF6bDVLSmdDdDlOWkhJempJdVo2aHhWNktKZ0N0OUpmMS92QUhPYmxoYUxHWG9nbEFLLzM1Y3YzdnEwT04zRWJkUFAvaENDYWZ0ck9Ya2dsQUsyMDN4WS9QYlYrKzFxRnJpdUtuLytsZk1yUFlTOWtFb0szT2JEVS9PTk03L2ZtdjNUYnE1aWZ2YnY5anZSN0hxbWdqZXlsV1o5SUw0TnE5ZmJWNThIVHZlemRVM3o1WWZXV3hYSzdLUGY3eFpsMjhzOVdjM0tpZi85RDFHanZaUzVrRW9OMjJtK0tGaS9VTEYxMkNNU3g3S1pCSFFBQ2hCQUFnbEFBQWhCSUFnRkFDQUJCS0FBQkNDUUJBS0FFQUNDVUFBS0VFQUNDVUFBeGxKRzlUK3RTRGU4c1M3V2RHcHBrQURPWHMxaGdQZm1GN2pBZUg2OE9NVERNQkdNckpqVEYrYzlicm03NldpOVl6STlOTUFJYnk0cVgrY0M5VDJzc3I2MjV2YVQwek1zMEVZQ2puZThXekg0emxDOUZQYlRhdnVicWgvY3pJTkp0YlhsNmE5QnJhN2MyUG1yVnV0VEsvMXdzMFBxLzFmdkhvMlczdldXSTJtSkdwSlFERHFvdmlYMWVhTzdyVmtSSHQ3L1YrOGRpNTNsdmp1MjJHNjh1TVRDMEJHSUd0cHZqN2VqMWZsbC9yRmxVeDFCWS90ZGs4ZW5iYnptYkdtSkhwVks2czNEenBOY3lPNHd2bC9RZXJ1NWFxV3hhS3BUM2ZxdnB4bTNWeHZ0ZThzVm0vdk82WkpqUE9qRXdWQVFBSTVhK0FBRUlKQUVBb0FRQUlKUUFBb1FRQUlKUUFBSVFTQUlCUUFnQVFTZ0FBUWdrQVFDZ0JBQWdsQUFDaEJBQWdsQUFBaEJJQWdGQUNBQkJLQUFCQ0NRQkFLQUVBQ0NVQUFLRUVBQ0NVQUFDRUVnQ0FVQUlBRUVvQUFFSUpBRUFvQVFBSUpRQUFvUVFBSUpRQUFJUVNBSUJRQWdBUVNnQUFRZ2tBUUNnQkFBZ2xBQUNoQkFBZ2xBQUFoQklBZ0ZBQ0FCQktBQUJDQ1FCQUtBRUFDQ1VBQUtFRUFDQ1VBQUNFRWdDQVVBSUFFRW9BQUVJSkFFQW9BUUFJSlFBQW9RUUFJSlFBQUlRU0FJQlFBZ0FRU2dBQVFna0FRQ2dCQUFnbEFBQ2hCQUFnbEFBQWhCSUFnRkFDQUJCS0FBQkNDUUJBS0FFQUNDVUFBS0VFQUNDVUFBQ0VFZ0NBVUFJQUVFb0FBRUlKQUVBb0FRQUlKUUFBb1FRQUlKUUFBSVFTQUlCUUFnQVFTZ0FBUWdrQVFDZ0JBQWdsQUFDaEJBQWdsQUFBaEJJQWdGQUNBQkJLQUFCQ0NRQkFLQUVBQ0NVQUFLRUVBQ0NVQUFDRUVnQ0FVQUlBRUVvQUFFSUpBRUFvQVFBSUpRQUFvUVFBSUpRQUFJUVNBSUJRQWdBUVNnQUFRZ2tBUUNnQkFBZ2xBQUNoQkFBZ2xBQUFoQklBZ0ZBQ0FCQktBQUJDQ1FCQUtBRUFDQ1VBQUtFRUFDQ1VBQUNFRWdDQVVBSUFFRW9BQUVJSkFFQW9BUUFJSlFBQW9RUUFJSlFBQUlRU0FJQlFBZ0FRU2dBQVFna0FRQ2dCQUFnbEFBQ2hCQUFnbEFBQWhCSUFnRkFDQUJCS0FBQkNDUUJBS0FFQUNDVUFBS0VFQUNDVUFBQ0VFZ0NBVUFJQUVFb0FBRUlKQUVBb0FRQUlKUUFBb1FRQUlKUUFBSVFTQUlCUUFnQVFTZ0FBUWdrQVFDZ0JBQWdsQUFDaEJBQWdsQUFBaEJJQWdGQUNBQkJLQUFCQ0NRQkFLQUVBQ0NVQUFLRUVBQ0NVQUFDRUVnQ0FVQUlBRUVvQUFFSUpBRUFvQVFBSUpRQUFvUVFBSUpRQUFJUVNBSUJRQWdBUVNnQUFRZ2tBUUNnQkFBZ2xBQUNoQkFBZ2xBQUFoQklBZ0ZBQ0FCQktBQUJDQ1FCQUtBRUFDQ1VBQUtFRUFDQ1VBQUNFRWdDQVVBSUFFRW9BQUVMOUQ3dHBVMzE4TFRnUUFBQUFBRWxGVGtTdVFtQ0MiLCAic2l6ZXMiOiAiNTEyeDUxMiIsICJ0eXBlIjogImltYWdlL3BuZyIsICJwdXJwb3NlIjogImFueSBtYXNrYWJsZSJ9XX0=">
<title>Trainings-Engine · Kraftsport</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Anton&family=Hanken+Grotesk:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
  :root{--bg:#EEEBE3;--paper:#FFFFFF;--ink:#191916;--muted:#6E6B62;--line:#DAD7CD;
    --accent:#E8431D;--accent-dark:#B22C0F;--hi:#E0524B;--mid:#EFA63A;--lo:#F2D06B;--none:#CFCDC4;
    --ok:#3F8F5B;--okbg:#e4efe7;--warnbg:#fbe7e1;--blue:#2f6f9e;--r:14px;}
  *{box-sizing:border-box;margin:0;padding:0}
  body{background:var(--bg);color:var(--ink);font-family:"Hanken Grotesk",sans-serif;line-height:1.55;padding:24px 16px 70px;-webkit-font-smoothing:antialiased}
  .wrap{max-width:1060px;margin:0 auto}
  h1{font-family:"Anton",sans-serif;font-weight:400;font-size:clamp(28px,5vw,46px);line-height:.95;letter-spacing:.5px;text-transform:uppercase}
  h1 .dot{color:var(--accent)}
  .lede{color:var(--muted);max-width:64ch;margin-top:8px;font-size:14.5px}
  .tabs{display:flex;gap:6px;margin-top:22px;border-bottom:1px solid var(--line)}
  .tab{font-family:"Anton",sans-serif;letter-spacing:1px;text-transform:uppercase;font-size:14px;background:none;border:none;
    color:var(--muted);padding:12px 18px;cursor:pointer;border-bottom:3px solid transparent;margin-bottom:-1px}
  .tab.on{color:var(--ink);border-bottom-color:var(--accent)}
  .view{display:none} .view.on{display:block}
  .panel{background:var(--paper);border:1px solid var(--line);border-radius:var(--r);padding:22px;margin-top:20px}
  .sec-h{font-family:"Anton",sans-serif;font-size:12px;letter-spacing:1.5px;text-transform:uppercase;color:var(--muted);margin-bottom:11px}
  .row{display:flex;flex-wrap:wrap;gap:9px}
  .grid-ctrl{display:grid;grid-template-columns:repeat(auto-fit,minmax(190px,1fr));gap:20px;margin-top:20px}
  .chip{border:1.5px solid var(--line);background:var(--paper);color:var(--ink);border-radius:999px;padding:8px 15px;font:inherit;font-weight:600;font-size:14px;cursor:pointer;transition:.15s;user-select:none}
  .chip:hover{border-color:var(--ink)} .chip.on{background:var(--ink);color:#fff;border-color:var(--ink)} .chip.day.on{background:var(--accent);border-color:var(--accent)}
  .goals{display:grid;grid-template-columns:repeat(3,1fr);gap:12px}
  @media(max-width:620px){.goals{grid-template-columns:1fr}}
  .goal{border:1.5px solid var(--line);border-radius:12px;padding:13px 15px;cursor:pointer;transition:.15s;background:var(--paper)}
  .goal:hover{border-color:var(--ink)} .goal.on{border-color:var(--accent);background:#fdf1ec;box-shadow:inset 0 0 0 1px var(--accent)}
  .goal h3{font-family:"Anton",sans-serif;font-weight:400;font-size:18px;letter-spacing:.5px;text-transform:uppercase}
  .goal p{font-size:12px;color:var(--muted);margin-top:3px;line-height:1.35} .goal .params{font-size:11.5px;color:var(--accent-dark);font-weight:600;margin-top:6px}
  .gen{font-family:"Anton",sans-serif;letter-spacing:1px;text-transform:uppercase;font-size:17px;background:var(--accent);color:#fff;border:none;border-radius:var(--r);padding:15px 26px;cursor:pointer;transition:.15s;width:100%;margin-top:22px}
  .gen:hover{background:var(--accent-dark)}
  .btn{border:1.5px solid var(--line);background:var(--paper);border-radius:10px;padding:9px 15px;font:inherit;font-weight:600;font-size:13.5px;cursor:pointer}
  .btn:hover{border-color:var(--ink)} .btn.accent{background:var(--accent);color:#fff;border-color:var(--accent)} .btn.accent:hover{background:var(--accent-dark)}
  .weeks{display:flex;gap:7px;flex-wrap:wrap;margin-top:6px}
  .wbtn{border:1.5px solid var(--line);background:var(--paper);border-radius:10px;padding:8px 13px;font:inherit;font-weight:600;font-size:13px;cursor:pointer;text-align:center;line-height:1.2}
  .wbtn small{display:block;font-size:10px;color:var(--muted);font-weight:600}
  .wbtn.on{background:var(--ink);color:#fff;border-color:var(--ink)} .wbtn.on small{color:#cfcdc4}
  .wbtn.deload{border-style:dashed} .wbtn.on.deload{background:var(--blue);border-color:var(--blue)}
  .card{background:var(--paper);border:1px solid var(--line);border-radius:var(--r);padding:18px 20px;margin-top:16px;overflow:hidden}
  .day-head{display:flex;align-items:center;gap:11px;border-bottom:2px solid var(--ink);padding-bottom:9px;margin-bottom:4px}
  .day-num{font-family:"Anton",sans-serif;font-size:26px;color:var(--accent);line-height:1}
  .day-title{font-family:"Anton",sans-serif;font-size:19px;text-transform:uppercase;letter-spacing:.5px;flex:1}
  .ex{display:flex;align-items:center;gap:12px;padding:11px 0;border-bottom:1px solid var(--line)} .ex:last-child{border-bottom:none}
  .ex-main{flex:1;min-width:0} .ex-name{font-weight:600;font-size:15px} .ex-name .iso{font-size:10.5px;font-weight:700;color:var(--muted);text-transform:uppercase;letter-spacing:.4px;margin-left:6px}
  .ex-meta{font-size:12px;color:var(--muted);margin-top:3px;display:flex;flex-wrap:wrap;gap:5px;align-items:center}
  .tag{font-size:10px;font-weight:700;text-transform:uppercase;letter-spacing:.4px;padding:2px 6px;border-radius:5px;background:var(--bg);color:var(--muted)} .tag.mus{background:#fbe7e1;color:var(--accent-dark)}
  .pres{font-size:12.5px;font-weight:600;text-align:right;white-space:nowrap} .pres .kg{color:var(--accent-dark);font-family:"Anton",sans-serif;font-size:15px;letter-spacing:.3px}
  .swap{border:1px solid var(--line);background:var(--paper);border-radius:8px;width:30px;height:30px;cursor:pointer;flex:none;color:var(--muted)} .swap:hover{border-color:var(--ink);color:var(--ink)}
  .a-grid{display:grid;grid-template-columns:1.15fr .85fr;gap:24px;align-items:start} @media(max-width:780px){.a-grid{grid-template-columns:1fr}}
  .vrow{display:grid;grid-template-columns:92px 1fr 66px;gap:8px;align-items:center;font-size:12.5px;margin-bottom:6px}
  .vtrack{position:relative;background:var(--bg);border-radius:6px;height:17px;overflow:hidden}
  .vzone{position:absolute;top:0;bottom:0;background:rgba(63,143,91,.15);border-left:1px dashed rgba(63,143,91,.55);border-right:1px dashed rgba(63,143,91,.55)}
  .vfill{position:absolute;top:0;bottom:0;left:0;border-radius:6px;transition:width .5s}
  .vval{font-weight:600;font-size:12px;text-align:right} .vval .fq{display:inline-block;font-size:9.5px;padding:1px 4px;border-radius:4px;margin-left:2px;font-weight:700}
  .fq.good{background:var(--okbg);color:var(--ok)} .fq.low{background:var(--warnbg);color:var(--accent-dark)}
  .kpis{display:flex;gap:10px;flex-wrap:wrap;margin-top:8px} .kpi{flex:1;min-width:120px;border:1px solid var(--line);border-radius:12px;padding:11px 13px}
  .kpi .lbl{font-size:10.5px;text-transform:uppercase;letter-spacing:.5px;color:var(--muted);font-weight:700} .kpi .big{font-family:"Anton",sans-serif;font-size:22px;margin-top:2px} .kpi .st{font-size:11.5px;font-weight:600;margin-top:1px}
  .st.ok{color:var(--ok)} .st.warn{color:var(--accent-dark)}
  .note{background:var(--warnbg);border:1px solid #f3c4b5;border-radius:10px;padding:10px 13px;font-size:13px;margin-top:13px;color:var(--accent-dark)} .note b{font-weight:700}
  .legend{display:flex;gap:13px;flex-wrap:wrap;font-size:11px;color:var(--muted);margin-top:11px} .legend span{display:flex;align-items:center;gap:5px} .sw{width:11px;height:11px;border-radius:3px;display:inline-block}
  /* training */
  .timer-wrap{position:fixed;left:50%;transform:translateX(-50%);bottom:14px;z-index:50;background:var(--paper);border:1px solid var(--line);border-radius:var(--r);padding:14px 18px;display:flex;align-items:center;gap:16px;flex-wrap:wrap;width:min(560px,calc(100% - 20px));box-shadow:0 8px 28px rgba(0,0,0,.16)}
  .timer-full{display:flex;align-items:center;gap:16px;flex-wrap:wrap;width:100%}
  .timer-min-only{display:none;align-items:center;gap:11px}
  .timer-wrap.min{width:auto;left:auto;right:14px;transform:none;padding:9px 12px 9px 15px}
  .timer-wrap.min .timer-full{display:none} .timer-wrap.min .timer-min-only{display:flex}
  .t-dot{width:13px;height:13px;border-radius:50%;background:var(--none);flex:none}
  .timer-ring{position:relative;width:84px;height:84px;flex:none}
  .timer-ring svg{transform:rotate(-90deg)}
  .timer-val{position:absolute;inset:0;display:flex;flex-direction:column;align-items:center;justify-content:center;font-family:"Anton",sans-serif;font-size:20px;line-height:1}
  .timer-val small{font-family:"Hanken Grotesk";font-size:10px;color:var(--muted);font-weight:600}
  .timer-info{flex:1;min-width:140px} .timer-state{font-family:"Anton",sans-serif;font-size:17px;text-transform:uppercase;letter-spacing:.5px}
  .timer-sub{font-size:12.5px;color:var(--muted)} .timer-btns{display:flex;gap:7px;flex-wrap:wrap}
  .tbtn{border:1.5px solid var(--line);background:var(--paper);border-radius:9px;padding:8px 12px;font:inherit;font-weight:600;font-size:13px;cursor:pointer} .tbtn:hover{border-color:var(--ink)}
  .preset{font-size:12px;padding:6px 10px}
  .logex{padding:13px 0;border-bottom:1px solid var(--line)} .logex:last-child{border-bottom:none}
  .logex-h{display:flex;justify-content:space-between;align-items:baseline;gap:10px;margin-bottom:8px}
  .logex-h .nm{font-weight:600;font-size:15px} .logex-h .tg{font-size:11.5px;color:var(--muted);white-space:nowrap}
  .setrow{display:grid;grid-template-columns:34px 1fr 1fr 40px;gap:8px;align-items:center;margin-bottom:6px}
  .setrow .sn{font-size:12px;color:var(--muted);font-weight:600;text-align:center}
  .setrow input{width:100%;border:1.5px solid var(--line);border-radius:8px;padding:8px;font:inherit;font-size:14px;text-align:center;background:var(--bg)}
  .setrow input:focus{outline:none;border-color:var(--accent);background:#fff}
  .setrow .chk{border:1.5px solid var(--line);background:var(--paper);border-radius:8px;height:36px;cursor:pointer;color:var(--muted);font-size:15px} .setrow.done .chk{background:var(--ok);border-color:var(--ok);color:#fff} .setrow.done input{opacity:.6}
  .hint{font-size:12px;color:var(--muted);margin:8px 0}
  .empty{color:var(--muted);text-align:center;padding:40px 0;font-size:15px}
  .pill{display:inline-block;font-size:11px;font-weight:700;padding:3px 9px;border-radius:999px;background:var(--bg);color:var(--muted)} .pill.dl{background:#e7eef4;color:var(--blue)}
  .stat-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(130px,1fr));gap:12px}
  .stat{border:1px solid var(--line);border-radius:12px;padding:14px} .stat .n{font-family:"Anton",sans-serif;font-size:28px} .stat .l{font-size:11.5px;color:var(--muted);text-transform:uppercase;letter-spacing:.5px;font-weight:700}
  .sess{display:flex;justify-content:space-between;gap:10px;padding:10px 0;border-bottom:1px solid var(--line);font-size:13.5px} .sess:last-child{border-bottom:none}
  .sess .dt{color:var(--muted);font-size:12px}
  select{border:1.5px solid var(--line);border-radius:9px;padding:8px 12px;font:inherit;font-size:14px;background:var(--paper);cursor:pointer}
  details.method{margin-top:18px;background:var(--paper);border:1px solid var(--line);border-radius:var(--r);padding:2px 22px}
  details.method summary{font-family:"Anton",sans-serif;font-size:13px;letter-spacing:1px;text-transform:uppercase;cursor:pointer;padding:15px 0;color:var(--muted)} details.method[open] summary{color:var(--ink)}
  .method p{font-size:13px;margin:0 0 11px;color:#3a3833;line-height:1.55} .method b{font-weight:600}
  footer{margin-top:28px;color:var(--muted);font-size:11.5px;text-align:center;line-height:1.6}
  .modal-bg{position:fixed;inset:0;background:rgba(0,0,0,.42);display:flex;align-items:center;justify-content:center;z-index:100;padding:18px}
  .modal{background:var(--paper);border-radius:var(--r);padding:22px;width:min(430px,100%);max-height:90vh;overflow:auto;box-shadow:0 12px 40px rgba(0,0,0,.25)}
  .modal-h{display:flex;justify-content:space-between;align-items:center;font-family:"Anton",sans-serif;font-size:17px;text-transform:uppercase;letter-spacing:.5px;margin-bottom:14px}
  .modal input,.modal select{border:1.5px solid var(--line);border-radius:8px;padding:9px;font:inherit;font-size:15px;background:var(--bg)}
  .modal input:focus,.modal select:focus{outline:none;border-color:var(--accent);background:#fff}
  .e1tag{cursor:pointer;background:#eef!important;color:#4a5d80!important}
  .e1tag:hover{background:#dde2f0!important}
  .e1row{display:flex;justify-content:space-between;align-items:center;gap:10px;padding:9px 0;border-bottom:1px solid var(--line);font-size:14px} .e1row:last-child{border-bottom:none}
  .e1row input{width:78px;border:1.5px solid var(--line);border-radius:7px;padding:6px;font:inherit;text-align:center;background:var(--bg)}
  #v-train{padding-bottom:120px}
  @media(max-width:560px){
    .ex{flex-wrap:wrap} .ex-main{flex:1 1 auto;min-width:0} .swap{order:2}
    .pres{order:3;width:100%;text-align:left;margin-top:5px;white-space:normal}
    .logex-h{flex-wrap:wrap} .logex-h .tg{white-space:normal;flex-basis:100%;margin-top:2px}
    .day-head{flex-wrap:wrap;row-gap:6px}
  }
  @media print{.tabs,.panel,.gen,.timer-wrap,details.method,.btn,footer .np{display:none}.view{display:block!important}.card{break-inside:avoid}}
</style>
</head>
<body>
<div class="wrap">
  <header>
    <h1>Trainings<span class="dot">.</span>Engine</h1>
    <p class="lede">Evidenzbasierter Generator mit Periodisierung, Lastberechnung, Volumen-Landmarks (MEV–MRV),
      Trainingslog und Pausentimer. Belastungssteuerung nach NSCA/ACSM.</p>
  </header>
  <div class="tabs">
    <button class="tab on" data-v="plan" onclick="showView('plan')">Plan</button>
    <button class="tab" data-v="train" onclick="showView('train')">Training</button>
    <button class="tab" data-v="hist" onclick="showView('hist')">Verlauf</button>
  </div>

  <!-- ===== PLAN ===== -->
  <section class="view on" id="v-plan">
    <div class="panel">
      <div class="sec-h">Trainingsziel</div>
      <div class="goals" id="goals"></div>
      <div class="grid-ctrl">
        <div><div class="sec-h">Tage / Woche</div><div class="row" id="days"></div></div>
        <div><div class="sec-h">Erfahrung</div><div class="row" id="level"></div></div>
        <div><div class="sec-h">Split</div><div class="row" id="split"></div></div>
        <div><div class="sec-h">Blocklänge</div><div class="row" id="block"></div></div>
      </div>
      <div style="margin-top:20px"><div class="sec-h">Equipment</div><div class="row" id="equip"></div></div>
      <button class="gen" onclick="makePlan()">Trainingsblock erstellen</button>
    </div>
    <div id="plan-out"><p class="empty">Ziel und Parameter wählen, dann Trainingsblock erstellen.</p></div>
    <details class="method">
      <summary>Methodik &amp; wissenschaftliche Grundlage</summary>
      <p><b>Belastung (NSCA-Kontinuum).</b> Maximalkraft ≥85&nbsp;% 1RM / ≤6&nbsp;Wdh / 2–5&nbsp;min Pause;
        Hypertrophie ~67–85&nbsp;% / 6–12&nbsp;Wdh / moderate Pausen; Kraftausdauer ≤67&nbsp;% / ≥15&nbsp;Wdh / kurze Pausen.</p>
      <p><b>Übungsreihenfolge.</b> Die Einheit beginnt mit den anspruchsvollsten Mehrgelenkübungen (große Muskelgruppen),
        gefolgt von Isolationsübungen; der Rumpf wird ans Ende gesetzt. Begründung: Übungen am Anfang werden mit höherer
        Last/Leistung ausgeführt, da noch keine Ermüdung vorliegt – die priorisierten Bewegungen gehören also nach vorn
        (ACSM-Empfehlung; Simão et al.). „Vorermüdung" (Isolation vor Grundübung) verbessert Kraft und Aktivierung dagegen nicht.</p>
      <p><b>Periodisierung.</b> Mehrwochen-Block mit progressiver Überlastung: Kraft über steigende Intensität (% 1RM ↑, Wdh ↓),
        Hypertrophie über Volumenakkumulation (Sätze ↑), jeweils abschließende Deload-Woche zur Regeneration.</p>
      <p><b>Volumen-Landmarks (MEV–MRV).</b> Pro Muskelgruppe ein produktiver Korridor zwischen minimal effektivem (MEV)
        und maximal regenerierbarem Volumen (MRV); Richtwerte nach dem Modell von Israetel/Renaissance Periodization.
        Sekundärmuskeln zählen als halbe Sätze.</p>
      <p><b>Frequenz &amp; Anstrengung.</b> Jede Muskelgruppe ≥2×/Woche; Steuerung über RIR (Hypertrophie 0–3, Kraft 1–2).
        Lastberechnung über geschätztes 1RM (Epley-Formel) aus deinen Log-Daten.</p>
      <p><b>Aktualität.</b> Die ACSM-Position 2026 betont höheres Wochenvolumen für Hypertrophie und Muskelaufbau über ein
        breites Lastspektrum bei ausreichender Anstrengung. Werte sind Ausgangspunkte und individuell anzupassen.</p>
    </details>
  </section>

  <!-- ===== TRAINING ===== -->
  <section class="view" id="v-train">
    <div id="train-out"><p class="empty">Erstelle zuerst einen Plan, wähle dann Trainingstag und Woche.</p></div>
  </section>

  <!-- ===== HISTORY ===== -->
  <section class="view" id="v-hist"><div id="hist-out"></div></section>

  <footer><p class="np">Orientierungshilfe, kein Ersatz für ärztliche Beratung oder individuelles Coaching.
    Daten werden lokal im Browser gespeichert (in dieser Vorschau ggf. nur temporär).</p></footer>
</div>

<div id="modal" class="modal-bg" style="display:none">
  <div class="modal">
    <div class="modal-h"><span id="m-title">1RM festlegen</span><button class="tbtn" onclick="closeModal()">✕</button></div>
    <div id="m-pick" style="display:none;margin-bottom:14px"><div class="sec-h">Übung</div><select id="m-sel" style="width:100%"></select></div>
    <div class="sec-h">1RM direkt eingeben</div>
    <div class="row" style="align-items:center;gap:8px"><input id="m-1rm" type="number" inputmode="decimal" placeholder="z. B. 120" style="flex:1"><span class="hint" style="margin:0">kg</span></div>
    <div class="sec-h" style="margin-top:16px">… oder aus einem Testsatz berechnen</div>
    <div class="row" style="align-items:center;gap:7px">
      <input id="m-w" type="number" inputmode="decimal" placeholder="Gewicht" oninput="calcE1()" style="width:90px">
      <span>×</span><input id="m-r" type="number" inputmode="numeric" placeholder="Wdh" oninput="calcE1()" style="width:70px">
      <span>=</span><span id="m-calc" style="font-family:'Anton',sans-serif;font-size:16px;min-width:54px">– kg</span>
      <button class="btn" onclick="useCalc()" title="übernehmen">↑</button></div>
    <p class="hint" style="margin-top:6px">Schätzung nach Epley-Formel.</p>
    <div style="display:flex;gap:8px;margin-top:16px;flex-wrap:wrap">
      <button class="btn accent" onclick="saveE1()">Speichern</button>
      <button class="btn" onclick="removeE1()">Entfernen</button>
      <button class="btn" onclick="closeModal()">Abbrechen</button></div>
  </div>
</div>

<script>
// ============ STORAGE (localStorage + in-memory fallback) ============
const Store={mem:{},
  get(k){try{const v=localStorage.getItem(k);return v===null?(this.mem[k]??null):v;}catch(e){return this.mem[k]??null;}},
  set(k,v){try{localStorage.setItem(k,v);}catch(e){this.mem[k]=v;}}};
const jget=(k,d)=>{const v=Store.get(k);if(v==null)return d;try{return JSON.parse(v);}catch(e){return d;}};
const jset=(k,o)=>Store.set(k,JSON.stringify(o));

// ============ DATA ============
const C="comp",I="iso";
const EX=[
 {n:"Bankdrücken (LH)",pat:"hpush",eq:"bb",lvl:2,t:C,pri:["chest"],sec:["triceps","shoulders"]},
 {n:"Schrägbankdrücken (LH)",pat:"hpush",eq:"bb",lvl:2,t:C,pri:["chest","shoulders"],sec:["triceps"]},
 {n:"Enges Bankdrücken",pat:"hpush",eq:"bb",lvl:2,t:C,pri:["triceps","chest"],sec:["shoulders"]},
 {n:"Kurzhantel-Bankdrücken",pat:"hpush",eq:"db",lvl:1,t:C,pri:["chest"],sec:["triceps","shoulders"]},
 {n:"Schrägbankdrücken (KH)",pat:"hpush",eq:"db",lvl:2,t:C,pri:["chest","shoulders"],sec:["triceps"]},
 {n:"Brustpresse (Maschine)",pat:"hpush",eq:"ma",lvl:1,t:C,pri:["chest"],sec:["triceps","shoulders"]},
 {n:"Liegestütze",pat:"hpush",eq:"bw",lvl:1,t:C,pri:["chest","triceps"],sec:["shoulders","core"]},
 {n:"Dips (Brustfokus)",pat:"hpush",eq:"bw",lvl:2,t:C,pri:["chest","triceps"],sec:["shoulders"]},
 {n:"Kettlebell Floor Press",pat:"hpush",eq:"kb",lvl:2,t:C,pri:["chest","triceps"],sec:["shoulders"]},
 {n:"Schulterdrücken (LH)",pat:"vpush",eq:"bb",lvl:2,t:C,pri:["shoulders"],sec:["triceps"]},
 {n:"Schulterdrücken (KH)",pat:"vpush",eq:"db",lvl:1,t:C,pri:["shoulders"],sec:["triceps"]},
 {n:"Arnold Press",pat:"vpush",eq:"db",lvl:2,t:C,pri:["shoulders"],sec:["triceps"]},
 {n:"Kettlebell Overhead Press",pat:"vpush",eq:"kb",lvl:2,t:C,pri:["shoulders"],sec:["triceps","core"]},
 {n:"Schulterpresse (Maschine)",pat:"vpush",eq:"ma",lvl:1,t:C,pri:["shoulders"],sec:["triceps"]},
 {n:"Pike Push-ups",pat:"vpush",eq:"bw",lvl:2,t:C,pri:["shoulders"],sec:["triceps"]},
 {n:"Handstand-Liegestütze",pat:"vpush",eq:"bw",lvl:3,t:C,pri:["shoulders"],sec:["triceps","core"]},
 {n:"Langhantelrudern",pat:"hpull",eq:"bb",lvl:2,t:C,pri:["back"],sec:["biceps","shoulders"]},
 {n:"Pendlay Row",pat:"hpull",eq:"bb",lvl:3,t:C,pri:["back"],sec:["biceps"]},
 {n:"T-Bar Rudern",pat:"hpull",eq:"bb",lvl:2,t:C,pri:["back"],sec:["biceps"]},
 {n:"Kurzhantelrudern (einarmig)",pat:"hpull",eq:"db",lvl:1,t:C,pri:["back"],sec:["biceps"]},
 {n:"Kabelrudern (sitzend)",pat:"hpull",eq:"ma",lvl:1,t:C,pri:["back"],sec:["biceps"]},
 {n:"Maschinenrudern",pat:"hpull",eq:"ma",lvl:1,t:C,pri:["back"],sec:["biceps"]},
 {n:"Kettlebell Row",pat:"hpull",eq:"kb",lvl:1,t:C,pri:["back"],sec:["biceps"]},
 {n:"Umgekehrtes Rudern",pat:"hpull",eq:"bw",lvl:1,t:C,pri:["back"],sec:["biceps","core"]},
 {n:"Klimmzüge",pat:"vpull",eq:"bw",lvl:2,t:C,pri:["back"],sec:["biceps"]},
 {n:"Klimmzüge (eng/Untergriff)",pat:"vpull",eq:"bw",lvl:2,t:C,pri:["back","biceps"],sec:[]},
 {n:"Latzug (Maschine)",pat:"vpull",eq:"ma",lvl:1,t:C,pri:["back"],sec:["biceps"]},
 {n:"Klimmzüge (assistiert)",pat:"vpull",eq:"ma",lvl:1,t:C,pri:["back"],sec:["biceps"]},
 {n:"Kniebeuge (LH)",pat:"squat",eq:"bb",lvl:2,t:C,pri:["quads","glutes"],sec:["core","lowerback"]},
 {n:"Frontkniebeuge",pat:"squat",eq:"bb",lvl:3,t:C,pri:["quads"],sec:["glutes","core"]},
 {n:"Hackenschmidt-Kniebeuge",pat:"squat",eq:"ma",lvl:2,t:C,pri:["quads"],sec:["glutes"]},
 {n:"Beinpresse (Maschine)",pat:"squat",eq:"ma",lvl:1,t:C,pri:["quads","glutes"],sec:["hamstrings"]},
 {n:"Goblet Squat (KB)",pat:"squat",eq:"kb",lvl:1,t:C,pri:["quads","glutes"],sec:["core"]},
 {n:"Kettlebell Front Squat",pat:"squat",eq:"kb",lvl:2,t:C,pri:["quads","glutes"],sec:["core"]},
 {n:"Eigengewicht-Kniebeuge",pat:"squat",eq:"bw",lvl:1,t:C,pri:["quads","glutes"],sec:["core"]},
 {n:"Pistol Squat",pat:"squat",eq:"bw",lvl:3,t:C,pri:["quads","glutes"],sec:["core"]},
 {n:"Kreuzheben (LH)",pat:"hinge",eq:"bb",lvl:3,t:C,pri:["hamstrings","glutes","lowerback"],sec:["back","quads"]},
 {n:"Sumo-Kreuzheben",pat:"hinge",eq:"bb",lvl:3,t:C,pri:["glutes","quads","lowerback"],sec:["hamstrings","back"]},
 {n:"Rumänisches Kreuzheben (LH)",pat:"hinge",eq:"bb",lvl:2,t:C,pri:["hamstrings","glutes"],sec:["lowerback"]},
 {n:"RDL (Kurzhantel)",pat:"hinge",eq:"db",lvl:2,t:C,pri:["hamstrings","glutes"],sec:["lowerback"]},
 {n:"Hip Thrust (LH)",pat:"hinge",eq:"bb",lvl:1,t:C,pri:["glutes"],sec:["hamstrings"]},
 {n:"Kettlebell Swing",pat:"hinge",eq:"kb",lvl:2,t:C,pri:["glutes","hamstrings"],sec:["lowerback","core"]},
 {n:"Kettlebell Deadlift",pat:"hinge",eq:"kb",lvl:1,t:C,pri:["hamstrings","glutes"],sec:["lowerback"]},
 {n:"Glute Bridge",pat:"hinge",eq:"bw",lvl:1,t:C,pri:["glutes"],sec:["hamstrings"]},
 {n:"Hyperextension (Rückenstrecker)",pat:"hinge",eq:"bw",lvl:1,t:C,pri:["lowerback","glutes"],sec:["hamstrings"]},
 {n:"Ausfallschritte",pat:"lunge",eq:"bw",lvl:1,t:C,pri:["quads","glutes"],sec:["hamstrings"]},
 {n:"Walking Lunges (KH)",pat:"lunge",eq:"db",lvl:2,t:C,pri:["quads","glutes"],sec:["hamstrings"]},
 {n:"Bulgarian Split Squat",pat:"lunge",eq:"db",lvl:2,t:C,pri:["quads","glutes"],sec:["hamstrings"]},
 {n:"Step-ups (KH)",pat:"lunge",eq:"db",lvl:1,t:C,pri:["quads","glutes"],sec:["hamstrings"]},
 {n:"Kettlebell Lunge",pat:"lunge",eq:"kb",lvl:2,t:C,pri:["quads","glutes"],sec:["hamstrings"]},
 {n:"Kurzhantel-Fliegende",pat:"iso",eq:"db",lvl:1,t:I,pri:["chest"],sec:[]},
 {n:"Kabelzug Crossover",pat:"iso",eq:"ma",lvl:1,t:I,pri:["chest"],sec:[]},
 {n:"Pec Deck (Maschine)",pat:"iso",eq:"ma",lvl:1,t:I,pri:["chest"],sec:[]},
 {n:"Seitheben (KH)",pat:"iso",eq:"db",lvl:1,t:I,pri:["shoulders"],sec:[]},
 {n:"Seitheben (Kabel)",pat:"iso",eq:"ma",lvl:1,t:I,pri:["shoulders"],sec:[]},
 {n:"Reverse Flys (KH)",pat:"iso",eq:"db",lvl:1,t:I,pri:["shoulders"],sec:["back"]},
 {n:"Face Pulls",pat:"iso",eq:"ma",lvl:1,t:I,pri:["shoulders"],sec:["back"]},
 {n:"Frontheben (KH)",pat:"iso",eq:"db",lvl:1,t:I,pri:["shoulders"],sec:[]},
 {n:"Überzüge (Pullover, KH)",pat:"iso",eq:"db",lvl:2,t:I,pri:["back"],sec:["chest"]},
 {n:"Straight-Arm Pulldown",pat:"iso",eq:"ma",lvl:1,t:I,pri:["back"],sec:[]},
 {n:"Shrugs (Nackenheben, KH)",pat:"iso",eq:"db",lvl:1,t:I,pri:["back"],sec:[]},
 {n:"Bizeps-Curls (KH)",pat:"iso",eq:"db",lvl:1,t:I,pri:["biceps"],sec:[]},
 {n:"Hammer Curls",pat:"iso",eq:"db",lvl:1,t:I,pri:["biceps"],sec:[]},
 {n:"Langhantel-Curls",pat:"iso",eq:"bb",lvl:1,t:I,pri:["biceps"],sec:[]},
 {n:"Scott-Curls (Preacher)",pat:"iso",eq:"bb",lvl:1,t:I,pri:["biceps"],sec:[]},
 {n:"Kabel-Curls",pat:"iso",eq:"ma",lvl:1,t:I,pri:["biceps"],sec:[]},
 {n:"Trizepsdrücken Seil (Kabel)",pat:"iso",eq:"ma",lvl:1,t:I,pri:["triceps"],sec:[]},
 {n:"Skullcrusher (SZ-Hantel)",pat:"iso",eq:"bb",lvl:2,t:I,pri:["triceps"],sec:[]},
 {n:"Überkopf-Trizepsstrecken (KH)",pat:"iso",eq:"db",lvl:1,t:I,pri:["triceps"],sec:[]},
 {n:"Bank-Dips",pat:"iso",eq:"bw",lvl:1,t:I,pri:["triceps"],sec:["chest"]},
 {n:"Beinstrecker (Maschine)",pat:"iso",eq:"ma",lvl:1,t:I,pri:["quads"],sec:[]},
 {n:"Sissy Squat",pat:"iso",eq:"bw",lvl:2,t:I,pri:["quads"],sec:[]},
 {n:"Beinbeuger liegend (Maschine)",pat:"iso",eq:"ma",lvl:1,t:I,pri:["hamstrings"],sec:[]},
 {n:"Beinbeuger sitzend (Maschine)",pat:"iso",eq:"ma",lvl:1,t:I,pri:["hamstrings"],sec:[]},
 {n:"Nordic Hamstring Curl",pat:"iso",eq:"bw",lvl:3,t:I,pri:["hamstrings"],sec:[]},
 {n:"Glute Kickback (Kabel)",pat:"iso",eq:"ma",lvl:1,t:I,pri:["glutes"],sec:[]},
 {n:"Abduktoren (Maschine)",pat:"iso",eq:"ma",lvl:1,t:I,pri:["glutes"],sec:[]},
 {n:"Wadenheben stehend",pat:"calf",eq:"bw",lvl:1,t:I,pri:["calves"],sec:[]},
 {n:"Wadenheben stehend (Maschine)",pat:"calf",eq:"ma",lvl:1,t:I,pri:["calves"],sec:[]},
 {n:"Wadenheben sitzend (Soleus)",pat:"calf",eq:"ma",lvl:1,t:I,pri:["calves"],sec:[]},
 {n:"Wadenheben (KH)",pat:"calf",eq:"db",lvl:1,t:I,pri:["calves"],sec:[]},
 {n:"Plank",pat:"core",eq:"bw",lvl:1,t:I,pri:["core"],sec:[]},
 {n:"Hängendes Beinheben",pat:"core",eq:"bw",lvl:2,t:I,pri:["core"],sec:[]},
 {n:"Ab Wheel Rollout",pat:"core",eq:"bw",lvl:3,t:I,pri:["core"],sec:["lowerback"]},
 {n:"Cable Crunch",pat:"core",eq:"ma",lvl:1,t:I,pri:["core"],sec:[]},
 {n:"Russian Twist (KB)",pat:"core",eq:"kb",lvl:2,t:I,pri:["core"],sec:[]},
 {n:"Seitlicher Plank",pat:"core",eq:"bw",lvl:1,t:I,pri:["core"],sec:[]},
];
const SCHEME={
 strength:{comp:{sets:4,reps:"3–5",load:"85–90 %",restSec:180,rir:"1–2"},iso:{sets:3,reps:"6–8",load:"~80 %",restSec:120,rir:"1–2"},core:{sets:3,reps:"8–12",restSec:90,rir:"1–2"}},
 hypertrophy:{comp:{sets:4,reps:"6–10",load:"70–80 %",restSec:105,rir:"1–2"},iso:{sets:3,reps:"10–15",load:"65–75 %",restSec:75,rir:"0–2"},core:{sets:3,reps:"12–20",restSec:60,rir:"0–2"}},
 endurance:{comp:{sets:3,reps:"15–20",load:"50–60 %",restSec:45,rir:"1–2"},iso:{sets:3,reps:"15–25",load:"~50 %",restSec:30,rir:"1–2"},core:{sets:3,reps:"20–30",restSec:30,rir:"1–2"}},
};
const GOALS={strength:{label:"Maximalkraft",desc:"Maximale Kraft & neuronale Effizienz.",params:"≥85 % 1RM · 3–5 Wdh · lange Pausen"},
 hypertrophy:{label:"Hypertrophie",desc:"Muskelaufbau über Volumen & Spannung.",params:"70–80 % 1RM · 6–12 Wdh · hohes Volumen"},
 endurance:{label:"Kraftausdauer",desc:"Ermüdungswiderstand & Wdh-Leistung.",params:"≤60 % 1RM · 15–20+ Wdh · kurze Pausen"}};
const TPL={
 full_a:{label:"Ganzkörper A",comp:["squat","hpush","vpull","hinge"],iso:["calves","shoulders","biceps"]},
 full_b:{label:"Ganzkörper B",comp:["hinge","vpush","hpull","lunge"],iso:["calves","triceps","core"]},
 full_c:{label:"Ganzkörper C",comp:["squat","hpush","hpull","lunge"],iso:["shoulders","biceps","core"]},
 push:{label:"Push · Drücken",comp:["hpush","vpush","hpush"],iso:["shoulders","triceps","triceps"]},
 pull:{label:"Pull · Ziehen",comp:["vpull","hpull","hpull"],iso:["back","biceps","biceps"]},
 legs:{label:"Beine",comp:["squat","hinge","lunge"],iso:["quads","hamstrings","calves"]},
 upper:{label:"Oberkörper",comp:["hpush","vpull","vpush","hpull"],iso:["shoulders","biceps","triceps"]},
 lower:{label:"Unterkörper",comp:["squat","hinge","lunge"],iso:["hamstrings","quads","calves"]}};
const FB={vpull:["hpull"],vpush:["hpush"],hpull:["vpull"],hpush:["vpush"],lunge:["squat"],hinge:["squat"],squat:["lunge","hinge"]};
const MUS={chest:"Brust",back:"Rücken",shoulders:"Schultern",biceps:"Bizeps",triceps:"Trizeps",quads:"Quadrizeps",hamstrings:"Beinbeuger",glutes:"Gesäß",calves:"Waden",core:"Rumpf",lowerback:"unt. Rücken"};
const EQL={bw:"Eigengewicht",db:"Kurzhantel",bb:"Langhantel",kb:"Kettlebell",ma:"Maschine"};
const MORDER=["chest","back","shoulders","biceps","triceps","core","lowerback","glutes","quads","hamstrings","calves"];
const LM={chest:[8,22],back:[10,25],shoulders:[8,24],biceps:[6,20],triceps:[6,18],quads:[8,20],hamstrings:[6,18],glutes:[4,16],calves:[8,18],core:[0,22],lowerback:[2,12]};

// ============ STATE ============
const S=jget("tpe.cfg",{goal:"hypertrophy",days:4,level:"int",split:"auto",block:4,equip:["bw","db","bb","kb","ma"]});
S.equipSet=new Set(S.equip);
let PLAN=jget("tpe.plan",null);      // {config, days:[{label,idx,items:[{ex,slot}]}]}
let curWeek=1, trainSel={day:0,week:1};

// ============ HELPERS ============
function maxLvl(){return S.level==="beg"?1:(S.level==="adv"?3:2);}
function isoCount(){return S.goal==="strength"?1:(S.goal==="hypertrophy"?3:2);}
function dayList(){const d=S.days,sp=S.split,lv=S.level;
  if(sp==="full"){const r=["full_a","full_b","full_c"];return Array.from({length:d},(_,i)=>r[i%3]);}
  if(sp==="ul"){const r=["upper","lower"];return Array.from({length:d},(_,i)=>r[i%2]);}
  if(sp==="ppl"){const r=["push","pull","legs"];return Array.from({length:d},(_,i)=>r[i%3]);}
  if(d<=1)return["full_a"];if(d===2)return["upper","lower"];
  if(d===3)return lv==="beg"?["full_a","full_b","full_c"]:["push","pull","legs"];
  if(d===4)return["upper","lower","upper","lower"];if(d===5)return["push","pull","legs","upper","lower"];
  return["push","pull","legs","push","pull","legs"];}
function pickComp(pat,mx,used){for(const p of[pat,...(FB[pat]||[])]){let pool=EX.filter(e=>e.pat===p&&e.t===C&&S.equipSet.has(e.eq)&&e.lvl<=mx);if(!pool.length)continue;let f=pool.filter(e=>!used.has(e.n));let a=f.length?f:pool;return a[Math.floor(Math.random()*a.length)];}let any=EX.filter(e=>e.pat===pat&&S.equipSet.has(e.eq));return any.length?any[Math.floor(Math.random()*any.length)]:null;}
function pickIso(mus,mx,used){let pool=EX.filter(e=>(e.t===I||e.pat==="calf"||e.pat==="core")&&e.pri.includes(mus)&&S.equipSet.has(e.eq)&&e.lvl<=mx);if(!pool.length)pool=EX.filter(e=>e.pri.includes(mus)&&S.equipSet.has(e.eq)&&e.lvl<=mx);if(!pool.length)return null;let f=pool.filter(e=>!used.has(e.n));let a=f.length?f:pool;return a[Math.floor(Math.random()*a.length)];}

// periodization
function periodize(cat,week,total){
 const hasDL=total>=3,isDL=hasDL&&week===total,buildN=hasDL?total-1:total;
 const s=SCHEME[S.goal][cat];const k=Math.min(week,buildN),frac=buildN>1?(k-1)/(buildN-1):0;
 let sets=s.sets,reps=s.reps,loadStr=s.load||null,restSec=s.restSec,rir=s.rir,phase="Aufbau";
 if(cat==="core")return{sets:isDL?2:s.sets,reps:s.reps,loadStr:null,restSec:s.restSec,rir:isDL?"3–4":s.rir,phase:isDL?"Deload":"Basis",isDL};
 if(isDL){sets=Math.max(2,Math.round(s.sets/2));rir="3–4";phase="Deload";
  if(S.goal==="strength"){reps=cat==="comp"?"5":"8";loadStr=cat==="comp"?"~65 %":"~60 %";}
  else if(S.goal==="hypertrophy"){loadStr=cat==="comp"?"~60 %":"~55 %";}
  else{reps=s.reps;loadStr="~45 %";}
  return{sets,reps,loadStr,restSec,rir,phase,isDL};}
 if(S.goal==="strength"){if(cat==="comp"){const ld=Math.round(80+frac*10);reps=String(Math.round(6-frac*3));loadStr=ld+" %";phase=frac<0.5?"Aufbau":"Intensivierung";}else{reps="6–8";loadStr="~80 %";phase="Assistenz";}}
 else if(S.goal==="hypertrophy"){const add=Math.round(frac*2);sets=3+add;loadStr=s.load;reps=s.reps;phase=frac<0.34?"Aufbau":(frac<0.84?"Akkumulation":"Intensivierung");}
 else{const rhi=cat==="comp"?22:25;const r=Math.round(15+frac*(rhi-15));reps=r+"+";loadStr=s.load;sets=s.sets+(frac>0.6?1:0);phase="Aufbau";}
 return{sets,reps,loadStr,restSec,rir,phase,isDL:false};
}
function catOf(ex){return ex.pat==="core"?"core":(ex.t===C?"comp":"iso");}
// Exercise order: multi-joint/large before single-joint, core last (ACSM / Simão et al.)
const ORD={squat:1,hinge:1,hpush:2,vpull:2,vpush:3,hpull:3,lunge:4};
function ordKey(it){if(it.ex.pat==="core")return 90;if(it.ex.pat==="calf")return 80;if(catOf(it.ex)==="iso")return 50;return ORD[it.ex.pat]||10;}
function orderItems(items){return items.map((it,i)=>[it,i]).sort((a,b)=>(ordKey(a[0])-ordKey(b[0]))||(a[1]-b[1])).map(x=>x[0]);}
function e1RM(w,r){return Math.round(w*(1+r/30)*10)/10;}
function pctMid(ls){if(!ls)return null;const n=(ls.match(/\d+/g)||[]).map(Number);return n.length?n.reduce((a,b)=>a+b,0)/n.length:null;}
function workKg(name,loadStr){const e=jget("tpe.e1rm",{})[name];const p=pctMid(loadStr);if(!e||!p)return null;return Math.round(e*p/100/2.5)*2.5;}

// ============ GENERATE ============
function makePlan(){
 const mx=maxLvl(),used=new Set(),k=isoCount();
 const days=dayList().map((dt,i)=>{const tpl=TPL[dt],items=[];
  tpl.comp.forEach(pat=>{const ex=pickComp(pat,mx,used);if(ex){used.add(ex.n);items.push({ex,slot:{type:"comp",pat}});}});
  tpl.iso.slice(0,k).forEach(mus=>{const ex=pickIso(mus,mx,used);if(ex){used.add(ex.n);items.push({ex,slot:{type:"iso",mus}});}});
  if(!items.some(it=>it.ex.pat==="core")){const ex=pickIso("core",mx,used);if(ex){used.add(ex.n);items.push({ex,slot:{type:"iso",mus:"core"}});}}
  return{label:tpl.label,idx:i+1,items:orderItems(items)};});
 PLAN={config:{goal:S.goal,level:S.level,block:S.block},days};
 curWeek=1;jset("tpe.plan",PLAN);saveCfg();renderPlan();
}
function saveCfg(){S.equip=[...S.equipSet];jset("tpe.cfg",{goal:S.goal,days:S.days,level:S.level,split:S.split,block:S.block,equip:S.equip});}
function swap(di,ei){const it=PLAN.days[di].items[ei];const used=new Set();PLAN.days.forEach(p=>p.items.forEach(x=>used.add(x.ex.n)));used.delete(it.ex.n);let cand=it.slot.type==="comp"?pickComp(it.slot.pat,maxLvl(),used):pickIso(it.slot.mus,maxLvl(),used);if(cand){PLAN.days[di].items[ei]={ex:cand,slot:it.slot};jset("tpe.plan",PLAN);renderPlan();}}

// ============ ANALYSIS ============
function analyze(){const vol={},freq={};MORDER.forEach(m=>{vol[m]=0;freq[m]=0;});let push=0,pull=0;
 PLAN.days.forEach(p=>{const dp=new Set();p.items.forEach(it=>{const pr=periodize(catOf(it.ex),curWeek,PLAN.config.block);
   it.ex.pri.forEach(m=>{vol[m]+=pr.sets;dp.add(m);});it.ex.sec.forEach(m=>{vol[m]+=pr.sets*0.5;});
   if(["hpush","vpush"].includes(it.ex.pat))push+=pr.sets;if(["hpull","vpull"].includes(it.ex.pat))pull+=pr.sets;});
  dp.forEach(m=>freq[m]++);});
 return{vol,freq,push,pull};}
function dayMin(p){let s=360;p.items.forEach(it=>{const pr=periodize(catOf(it.ex),curWeek,PLAN.config.block);s+=pr.sets*(40+pr.restSec);});return Math.round(s/60);}
function heat(r){if(r<=0.05)return"var(--none)";if(r<0.34)return"var(--lo)";if(r<0.67)return"var(--mid)";return"var(--hi)";}
function volColor(m,v){const[mev,mrv]=LM[m];if(v<mev*0.6)return"var(--hi)";if(v<mev)return"var(--lo)";if(v>mrv)return"var(--mid)";return"var(--ok)";}
function fmt(v){return v%1?v.toFixed(1):v;}

// ============ RENDER: PLAN ============
function renderPlan(){
 const out=document.getElementById("plan-out");if(!PLAN){out.innerHTML='<p class="empty">Ziel und Parameter wählen, dann Trainingsblock erstellen.</p>';return;}
 const total=PLAN.config.block;const E1=jget("tpe.e1rm",{});
 let h=`<div class="card"><div class="day-head"><span class="day-title" style="color:var(--ink)">Trainingsblock · ${total} Wochen</span></div>
   <p class="hint">Woche wählen – Vorgaben passen sich an (Progression + Deload). Ziel: <b>${GOALS[PLAN.config.goal].label}</b></p><div class="weeks">`;
 for(let w=1;w<=total;w++){const dl=(total>=3&&w===total);
   h+=`<button class="wbtn ${w===curWeek?'on':''} ${dl?'deload':''}" onclick="setWeek(${w})">W${w}<small>${dl?'Deload':'Aufbau'}</small></button>`;}
 h+=`</div></div>`;
 PLAN.days.forEach((p,di)=>{
  h+=`<div class="card"><div class="day-head"><span class="day-num">${p.idx}</span><span class="day-title">${p.label}</span>
    <span class="pill ${weekIsDeload()?'dl':''}">W${curWeek}</span> <span class="hint" style="margin:0 8px">≈ ${dayMin(p)} min</span>
    <button class="btn accent" onclick="startWorkout(${di})">Training starten</button></div>`;
  p.items.forEach((it,ei)=>{const pr=periodize(catOf(it.ex),curWeek,total);
   const iso=catOf(it.ex)==="iso"?'<span class="iso">Iso</span>':"";
   const mus=it.ex.pri.map(m=>`<span class="tag mus">${MUS[m]}</span>`).join("");
   const e1cur=E1[it.ex.n];const kg=workKg(it.ex.n,pr.loadStr);
   const load=pr.loadStr&&it.ex.eq!=="bw"?` · ${pr.loadStr} 1RM`:"";
   h+=`<div class="ex"><div class="ex-main"><div class="ex-name">${it.ex.n}${iso}</div>
     <div class="ex-meta"><span class="tag">${EQL[it.ex.eq]}</span>${mus}<span class="tag" style="background:#eef;color:#557">${pr.phase}</span>
       <span class="tag e1tag" data-n="${it.ex.n}" onclick="openE1Modal(this.dataset.n)">1RM ${e1cur?e1cur+" kg ✎":"+"}</span></div></div>
     <div class="pres">${kg?`<span class="kg">≈ ${kg} kg</span><br>`:""}${pr.sets} × ${pr.reps}${load} · P ${secStr(pr.restSec)} · RIR ${pr.rir}</div>
     <button class="swap" title="tauschen" onclick="swap(${di},${ei})">↻</button></div>`;});
  h+=`</div>`;});
 // analysis
 const a=analyze(),maxV=Math.max(...MORDER.map(m=>a.vol[m]),24),scaleMax=Math.max(28,Math.ceil(maxV));
 h+=`<div class="card"><div class="day-head"><span class="day-title" style="color:var(--ink)">Wochenanalyse · W${curWeek}</span></div>
   <div class="a-grid"><div><p class="hint">Sätze/Muskel · grünes Band = MEV–MRV-Korridor · Frequenz: <b style="color:var(--ok)">●</b>≥2× <b style="color:var(--accent-dark)">●</b>&lt;2×</p>`;
 MORDER.forEach(m=>{const v=a.vol[m],[mev,mrv]=LM[m];const w=Math.min(v/scaleMax*100,100);
   const z0=mev/scaleMax*100,z1=Math.min(mrv,scaleMax)/scaleMax*100;
   const fq=a.freq[m]>=2?`<span class="fq good">${a.freq[m]}×</span>`:((a.freq[m]>0||v>0)?`<span class="fq low">${a.freq[m]}×</span>`:"");
   h+=`<div class="vrow"><span>${MUS[m]}</span><div class="vtrack"><div class="vzone" style="left:${z0}%;width:${z1-z0}%"></div>
     <div class="vfill" style="width:${w}%;background:${volColor(m,v)}"></div></div><span class="vval">${fmt(v)}${fq}</span></div>`;});
 const pp=a.pull>0?a.push/a.pull:0,ppOk=pp>=.7&&pp<=1.4;
 const qh=a.vol.hamstrings>0?a.vol.quads/a.vol.hamstrings:0,qhOk=qh>=.8&&qh<=2;
 h+=`<div class="kpis"><div class="kpi"><div class="lbl">Druck : Zug</div><div class="big">${a.push}:${a.pull}</div><div class="st ${ppOk?'ok':'warn'}">${ppOk?'ausgewogen':'unausgewogen'}</div></div>
   <div class="kpi"><div class="lbl">Quad : Beinbeuger</div><div class="big">${fmt(a.vol.quads)}:${fmt(a.vol.hamstrings)}</div><div class="st ${qhOk?'ok':'warn'}">${qhOk?'ausgewogen':'Rückseite prüfen'}</div></div></div>`;
 h+=`</div><div>${bodySVG()}<div class="legend"><span><i class="sw" style="background:var(--ok)"></i>im Korridor</span><span><i class="sw" style="background:var(--lo)"></i>unter MEV</span><span><i class="sw" style="background:var(--mid)"></i>über MRV</span><span><i class="sw" style="background:var(--hi)"></i>kaum</span></div>
   <p class="hint" style="margin-top:7px">Körperschema: relative Beanspruchung.</p></div></div>`;
 const low=MORDER.filter(m=>{const v=a.vol[m];return v>0&&v<LM[m][0];}),miss=MORDER.filter(m=>a.vol[m]===0);
 const over=MORDER.filter(m=>a.vol[m]>LM[m][1]),lowF=MORDER.filter(m=>a.vol[m]>=LM[m][0]&&a.freq[m]<2);
 let nt=[];if(miss.length)nt.push(`Nicht abgedeckt: <b>${miss.map(m=>MUS[m]).join(", ")}</b>`);
 if(low.length)nt.push(`Unter MEV: <b>${low.map(m=>MUS[m]).join(", ")}</b>`);
 if(over.length)nt.push(`Über MRV (Regeneration prüfen): <b>${over.map(m=>MUS[m]).join(", ")}</b>`);
 if(lowF.length)nt.push(`Nur 1×/Woche: <b>${lowF.map(m=>MUS[m]).join(", ")}</b> – auf 2 Tage verteilen`);
 if(nt.length)h+=`<div class="note"><b>Optimierungshinweise (W${curWeek}):</b><br>· ${nt.join("<br>· ")}</div>`;
 h+=`</div>`;
 out.innerHTML=h;
 MORDER.forEach(m=>{const r=a.vol[m]/Math.max(...MORDER.map(x=>a.vol[x]),1);document.querySelectorAll(`#plan-out [data-m="${m}"]`).forEach(el=>el.style.fill=heat(r));});
}
function weekIsDeload(){return PLAN&&PLAN.config.block>=3&&curWeek===PLAN.config.block;}
function setWeek(w){curWeek=w;renderPlan();}
function secStr(s){return s>=60?(s%60?Math.floor(s/60)+":"+String(s%60).padStart(2,"0")+" min":s/60+" min"):s+" s";}

// ============ TRAINING ============
let logState=null; // {di, week, ex:[{name, sets:[{w,r,done}], target}]}
function startWorkout(di){trainSel={day:di,week:curWeek};showView("train");buildLog();}
function buildLog(){
 if(!PLAN){document.getElementById("train-out").innerHTML='<p class="empty">Erstelle zuerst einen Plan.</p>';return;}
 const di=trainSel.day,wk=trainSel.week,day=PLAN.days[di];
 logState={di,week:wk,label:day.label,ex:day.items.map(it=>{const pr=periodize(catOf(it.ex),wk,PLAN.config.block);
   const kg=workKg(it.ex.n,pr.loadStr);
   return{name:it.ex.n,pat:it.ex.pat,target:pr,kg,sets:Array.from({length:pr.sets},()=>({w:kg||"",r:"",done:false}))};})};
 renderTrain();
}
function renderTrain(){
 const out=document.getElementById("train-out");if(!logState){out.innerHTML='<p class="empty">Erstelle zuerst einen Plan, wähle dann Trainingstag und Woche.</p>';return;}
 let opt="";PLAN.days.forEach((d,i)=>opt+=`<option value="${i}" ${i===logState.di?"selected":""}>Tag ${i+1}: ${d.label}</option>`);
 let wopt="";for(let w=1;w<=PLAN.config.block;w++)wopt+=`<option value="${w}" ${w===logState.week?"selected":""}>Woche ${w}${(PLAN.config.block>=3&&w===PLAN.config.block)?" (Deload)":""}</option>`;
 let h=`<div class="panel"><div class="row" style="align-items:center;gap:12px">
   <select onchange="trainSel.day=+this.value;buildLog()">${opt}</select>
   <select onchange="trainSel.week=+this.value;buildLog()">${wopt}</select>
   <span class="hint" style="margin:0">Gewicht &amp; Wdh eintragen, Satz mit ✓ abschließen – startet die Pause.</span></div></div>`;
 // timer
 h+=`<div class="timer-wrap ${timerMin?'min':''}" id="timerWrap">
   <div class="timer-full">
     <div class="timer-ring"><svg width="84" height="84" viewBox="0 0 84 84">
       <circle cx="42" cy="42" r="36" fill="none" stroke="var(--bg)" stroke-width="8"/>
       <circle id="tring" cx="42" cy="42" r="36" fill="none" stroke="var(--none)" stroke-width="8" stroke-linecap="round" stroke-dasharray="226" stroke-dashoffset="226"/></svg>
       <div class="timer-val"><span class="t-time">0:00</span><small id="ttgt">Ziel –</small></div></div>
     <div class="timer-info"><div class="timer-state t-state">Pausentimer</div><div class="timer-sub t-sub">Satz abschließen oder Zeit wählen</div></div>
     <div class="timer-btns">
       <button class="tbtn preset" onclick="startTimer(45)">45s</button><button class="tbtn preset" onclick="startTimer(90)">90s</button>
       <button class="tbtn preset" onclick="startTimer(120)">2min</button><button class="tbtn preset" onclick="startTimer(180)">3min</button>
       <button class="tbtn" onclick="pauseTimer()" id="tpause">⏸</button><button class="tbtn" onclick="stopTimer()">⏹</button>
       <button class="tbtn" onclick="toggleTimerMin()" title="Timer minimieren">▾</button></div>
   </div>
   <div class="timer-min-only">
     <span class="t-dot"></span><span class="t-time" style="font-family:'Anton',sans-serif;font-size:19px;letter-spacing:.5px">0:00</span>
     <span class="t-state" style="font-size:12.5px;font-weight:600;color:var(--muted)">Pause</span>
     <button class="tbtn" onclick="toggleTimerMin()" title="Timer aufklappen">▴</button></div>
   </div>`;
 // exercises
 h+=`<div class="card"><div class="day-head"><span class="day-num">${logState.di+1}</span><span class="day-title">${logState.label}</span><span class="pill ${(PLAN.config.block>=3&&logState.week===PLAN.config.block)?'dl':''}">W${logState.week}</span></div>`;
 logState.ex.forEach((e,xi)=>{const t=e.target;const load=t.loadStr&&!isBW(e.name)?` · ${t.loadStr}`:"";
  h+=`<div class="logex"><div class="logex-h"><span class="nm">${e.name}</span><span class="tg">Ziel: ${t.sets} × ${t.reps}${load} · RIR ${t.rir} · P ${secStr(t.restSec)}</span></div>`;
  e.sets.forEach((st,si)=>{h+=`<div class="setrow ${st.done?'done':''}" id="sr-${xi}-${si}">
    <span class="sn">${si+1}</span>
    <input type="number" inputmode="decimal" placeholder="kg" value="${st.w}" oninput="logState.ex[${xi}].sets[${si}].w=this.value">
    <input type="number" inputmode="numeric" placeholder="Wdh" value="${st.r}" oninput="logState.ex[${xi}].sets[${si}].r=this.value">
    <button class="chk" onclick="doneSet(${xi},${si})">✓</button></div>`;});
  h+=`</div>`;});
 h+=`<div style="margin-top:16px;display:flex;gap:10px;flex-wrap:wrap"><button class="btn accent" onclick="finishWorkout()">Einheit abschließen &amp; speichern</button>
   <button class="btn" onclick="showView('plan')">Zurück zum Plan</button></div></div>`;
 out.innerHTML=h;
}
function isBW(name){const e=EX.find(x=>x.n===name);return e&&e.eq==="bw";}
function doneSet(xi,si){const st=logState.ex[xi].sets[si];st.done=!st.done;const row=document.getElementById(`sr-${xi}-${si}`);row.classList.toggle("done",st.done);
 if(st.done){startTimer(logState.ex[xi].target.restSec);}}
function finishWorkout(){
 const entries=logState.ex.map(e=>({name:e.name,sets:e.sets.filter(s=>(+s.w>0||s.done)&&+s.r>0).map(s=>({w:+s.w||0,r:+s.r}))})).filter(e=>e.sets.length);
 if(!entries.length){alert("Noch keine Sätze mit Wiederholungen eingetragen.");return;}
 const totalSets=entries.reduce((a,e)=>a+e.sets.length,0);
 const log=jget("tpe.log",[]);
 log.unshift({id:Date.now(),date:new Date().toISOString(),week:logState.week,dayLabel:logState.label,entries,totalSets});
 jset("tpe.log",log);
 // update e1RM
 const e1=jget("tpe.e1rm",{});entries.forEach(e=>{e.sets.forEach(s=>{if(s.w>0&&s.r>0){const v=e1RM(s.w,s.r);if(!e1[e.name]||v>e1[e.name])e1[e.name]=v;}});});jset("tpe.e1rm",e1);
 stopTimer();alert("Einheit gespeichert ✓  ("+totalSets+" Sätze)");showView("hist");
}

// ============ TIMER ============
let timer={iv:null,el:0,tgt:0,run:false}, timerMin=false;
function toggleTimerMin(){timerMin=!timerMin;const w=document.getElementById("timerWrap");if(w)w.classList.toggle("min",timerMin);}
function startTimer(tgt){clearInterval(timer.iv);timer.tgt=tgt;timer.el=0;timer.run=true;tick();timer.iv=setInterval(()=>{if(timer.run){timer.el++;tick();}},1000);}
function pauseTimer(){timer.run=!timer.run;const b=document.getElementById("tpause");if(b)b.textContent=timer.run?"⏸":"▶";}
function stopTimer(){clearInterval(timer.iv);timer.run=false;timer.el=0;tick();const b=document.getElementById("tpause");if(b)b.textContent="⏸";}
function tick(){
 const times=document.querySelectorAll(".t-time");if(!times.length)return;
 const e=timer.el,t=timer.tgt,tstr=Math.floor(e/60)+":"+String(e%60).padStart(2,"0");
 times.forEach(el=>el.textContent=tstr);
 const tgtEl=document.getElementById("ttgt");if(tgtEl)tgtEl.textContent=t?("Ziel "+secStr(t)):"Ziel –";
 const ring=document.getElementById("tring");
 let col="var(--none)",label="Pause",msg="Satz abschließen oder Zeit wählen";
 if(t){const r=e/t;if(ring)ring.setAttribute("stroke-dashoffset",226-226*Math.min(r,1));
   if(r<0.6){col="var(--hi)";label="Noch erholen";msg="Muskel noch nicht regeneriert";}
   else if(r<0.95){col="var(--mid)";label="Fast bereit";msg="Gleich optimal";}
   else if(r<=1.5){col="var(--ok)";label="Optimales Fenster";msg="Jetzt nächsten Satz starten";}
   else{col="var(--blue)";label="Pause überzogen";msg="Länger als nötig – Satzleistung kann sinken";}
   if(ring)ring.setAttribute("stroke",col);}
 else if(ring){ring.setAttribute("stroke","var(--none)");ring.setAttribute("stroke-dashoffset",226);}
 document.querySelectorAll(".t-state").forEach(el=>{el.textContent=label;el.style.color=col;});
 document.querySelectorAll(".t-dot").forEach(el=>el.style.background=col);
 const sub=document.querySelector(".t-sub");if(sub)sub.textContent=msg;
}

// ============ 1RM MODAL & DATA ============
let modalEx=null;
function openE1Modal(name){modalEx=name||null;const e1=jget("tpe.e1rm",{});
 document.getElementById("m-title").textContent=name?name:"1RM hinzufügen";
 const pick=document.getElementById("m-pick");
 if(name){pick.style.display="none";}
 else{pick.style.display="block";const sel=document.getElementById("m-sel");
   sel.innerHTML=EX.map(e=>`<option>${e.n}</option>`).join("");}
 document.getElementById("m-1rm").value=name&&e1[name]?e1[name]:"";
 document.getElementById("m-w").value="";document.getElementById("m-r").value="";document.getElementById("m-calc").textContent="– kg";
 document.getElementById("modal").style.display="flex";}
function closeModal(){document.getElementById("modal").style.display="none";}
function calcE1(){const w=+document.getElementById("m-w").value,r=+document.getElementById("m-r").value;
 document.getElementById("m-calc").textContent=(w>0&&r>0)?e1RM(w,r)+" kg":"– kg";}
function useCalc(){const w=+document.getElementById("m-w").value,r=+document.getElementById("m-r").value;if(w>0&&r>0)document.getElementById("m-1rm").value=e1RM(w,r);}
function saveE1(){const name=modalEx||document.getElementById("m-sel").value;const v=+document.getElementById("m-1rm").value;
 if(!name){closeModal();return;}const e1=jget("tpe.e1rm",{});if(v>0)e1[name]=Math.round(v*10)/10;else delete e1[name];jset("tpe.e1rm",e1);
 closeModal();afterDataChange();}
function removeE1(){const name=modalEx||document.getElementById("m-sel").value;const e1=jget("tpe.e1rm",{});delete e1[name];jset("tpe.e1rm",e1);closeModal();afterDataChange();}
function setE1(name,val){const e1=jget("tpe.e1rm",{});const v=+val;if(v>0)e1[name]=Math.round(v*10)/10;else delete e1[name];jset("tpe.e1rm",e1);afterDataChange();}
function afterDataChange(){if(PLAN)renderPlan();const hv=document.getElementById("v-hist");if(hv&&hv.classList.contains("on"))renderHist();}
function exportData(){const data={app:"trainings-engine",v:1,exported:new Date().toISOString(),cfg:jget("tpe.cfg",{}),plan:jget("tpe.plan",null),e1rm:jget("tpe.e1rm",{}),log:jget("tpe.log",[])};
 const blob=new Blob([JSON.stringify(data,null,2)],{type:"application/json"});const url=URL.createObjectURL(blob);
 const a=document.createElement("a");a.href=url;a.download="trainings-engine-"+new Date().toISOString().slice(0,10)+".json";document.body.appendChild(a);a.click();a.remove();setTimeout(()=>URL.revokeObjectURL(url),1000);}
function importData(input){const f=input.files&&input.files[0];if(!f)return;const rd=new FileReader();
 rd.onload=()=>{try{const d=JSON.parse(rd.result);
   if(d.cfg)jset("tpe.cfg",d.cfg);if("plan" in d)jset("tpe.plan",d.plan);if(d.e1rm)jset("tpe.e1rm",d.e1rm);if(d.log)jset("tpe.log",d.log);
   const cfg=jget("tpe.cfg",{});Object.assign(S,cfg);S.equipSet=new Set(S.equip&&S.equip.length?S.equip:["bw","db","bb","kb","ma"]);
   PLAN=jget("tpe.plan",null);curWeek=1;logState=null;
   refresh();renderPlan();renderHist();alert("Daten erfolgreich importiert ✓");
 }catch(e){alert("Import fehlgeschlagen – ungültige oder beschädigte Datei.");}};
 rd.readAsText(f);input.value="";}

// ============ HISTORY ============
function histTopSections(e1){
 const entries=Object.entries(e1).sort((a,b)=>a[0].localeCompare(b[0]));
 let m=`<div class="panel"><div class="sec-h">1RM verwalten &amp; Lastrechner</div>
   <p class="hint">Hinterlege dein 1RM (oder geschätztes Maximum) pro Übung – daraus berechnet die App die Arbeitsgewichte im Plan.</p>
   <button class="btn accent" onclick="openE1Modal('')">+ Übung hinzufügen / berechnen</button>`;
 if(entries.length){m+='<div style="margin-top:12px">';entries.forEach(([n,v])=>{m+=`<div class="e1row"><span>${n}</span><span><input type="number" inputmode="decimal" value="${v}" onchange="setE1('${n}',this.value)"> kg</span></div>`;});m+='</div>';}
 else m+='<p class="hint" style="margin-top:10px">Noch keine 1RM-Werte gespeichert.</p>';
 m+='</div>';
 m+=`<div class="panel"><div class="sec-h">Daten sichern &amp; übertragen</div>
   <p class="hint">Exportiere deinen kompletten Stand (Plan, 1RM-Werte, Verlauf) als Datei – oder lade eine Sicherung, auch auf einem anderen Gerät.</p>
   <div class="row"><button class="btn accent" onclick="exportData()">⬇ Exportieren (JSON)</button>
     <label class="btn" style="cursor:pointer">⬆ Importieren<input type="file" accept="application/json,.json" style="display:none" onchange="importData(this)"></label></div></div>`;
 return m;
}
function renderHist(){
 const out=document.getElementById("hist-out");if(!out)return;const log=jget("tpe.log",[]),e1=jget("tpe.e1rm",{});
 const top=histTopSections(e1);
 if(!log.length){out.innerHTML=top+'<div class="panel"><p class="empty">Noch keine Einheiten gespeichert. Logge dein erstes Training im Bereich „Training".</p></div>';return;}
 const totalSets=log.reduce((a,s)=>a+s.totalSets,0);
 const days7=Date.now()-7*864e5,week=log.filter(s=>new Date(s.date).getTime()>days7).length;
 let h=`<div class="panel"><div class="sec-h">Übersicht</div><div class="stat-grid">
   <div class="stat"><div class="n">${log.length}</div><div class="l">Einheiten</div></div>
   <div class="stat"><div class="n">${totalSets}</div><div class="l">Sätze gesamt</div></div>
   <div class="stat"><div class="n">${week}</div><div class="l">letzte 7 Tage</div></div>
   <div class="stat"><div class="n">${Object.keys(e1).length}</div><div class="l">Übungen mit e1RM</div></div></div></div>`;
 // e1RM bestlist + chart
 const exNames=[...new Set(log.flatMap(s=>s.entries.map(e=>e.name)))];
 h+=`<div class="card"><div class="day-head"><span class="day-title" style="color:var(--ink)">Kraftentwicklung (e1RM)</span></div>
   <div class="row" style="margin-bottom:10px"><select id="exsel" onchange="drawE1()">${exNames.map(n=>`<option>${n}</option>`).join("")}</select></div>
   <div id="e1chart"></div></div>`;
 // volume trend
 h+=`<div class="card"><div class="day-head"><span class="day-title" style="color:var(--ink)">Volumen-Verlauf (Sätze/Einheit)</span></div><div id="volchart"></div></div>`;
 // sessions
 h+=`<div class="card"><div class="day-head"><span class="day-title" style="color:var(--ink)">Letzte Einheiten</span>
   <button class="btn" style="margin-left:auto" onclick="if(confirm('Gesamten Verlauf löschen?')){jset('tpe.log',[]);jset('tpe.e1rm',{});renderHist();}">Verlauf löschen</button></div>`;
 log.slice(0,12).forEach(s=>{const d=new Date(s.date);h+=`<div class="sess"><span><b>${s.dayLabel}</b> · W${s.week}<br><span class="dt">${d.toLocaleDateString("de-DE")} ${d.toLocaleTimeString("de-DE",{hour:"2-digit",minute:"2-digit"})}</span></span><span>${s.totalSets} Sätze</span></div>`;});
 h+=`</div>`;
 out.innerHTML=top+h;drawE1();drawVol();
}
function drawE1(){const log=jget("tpe.log",[]);const sel=document.getElementById("exsel");if(!sel)return;const name=sel.value;
 const pts=[];log.slice().reverse().forEach(s=>{s.entries.filter(e=>e.name===name).forEach(e=>{let mx=0;e.sets.forEach(st=>{if(st.w>0&&st.r>0)mx=Math.max(mx,e1RM(st.w,st.r));});if(mx)pts.push({x:new Date(s.date).getTime(),y:mx});});});
 document.getElementById("e1chart").innerHTML=pts.length>1?lineChart(pts,"kg"):'<p class="hint">Mindestens zwei Einträge nötig, um einen Verlauf zu zeichnen.</p>';}
function drawVol(){const log=jget("tpe.log",[]);const pts=log.slice().reverse().map(s=>({x:new Date(s.date).getTime(),y:s.totalSets}));
 document.getElementById("volchart").innerHTML=pts.length?barChart(pts):'<p class="hint">Noch keine Daten.</p>';}
function lineChart(pts,unit){const W=600,H=180,p=34;const xs=pts.map(o=>o.x),ys=pts.map(o=>o.y);
 const xmin=Math.min(...xs),xmax=Math.max(...xs),ymin=Math.min(...ys)*.95,ymax=Math.max(...ys)*1.05;
 const X=x=>p+(xmax===xmin?0.5:(x-xmin)/(xmax-xmin))*(W-2*p),Y=y=>H-p-(ymax===ymin?0.5:(y-ymin)/(ymax-ymin))*(H-2*p);
 let path=pts.map((o,i)=>(i?"L":"M")+X(o.x).toFixed(1)+" "+Y(o.y).toFixed(1)).join(" ");
 let dots=pts.map(o=>`<circle cx="${X(o.x).toFixed(1)}" cy="${Y(o.y).toFixed(1)}" r="3.5" fill="var(--accent)"/>`).join("");
 let yl=`<text x="4" y="${Y(ymax)+4}" font-size="11" fill="var(--muted)">${Math.round(ymax)}</text><text x="4" y="${Y(ymin)+4}" font-size="11" fill="var(--muted)">${Math.round(ymin)}</text>`;
 return `<svg width="100%" viewBox="0 0 ${W} ${H}"><line x1="${p}" y1="${H-p}" x2="${W-p}" y2="${H-p}" stroke="var(--line)"/><path d="${path}" fill="none" stroke="var(--accent)" stroke-width="2"/>${dots}${yl}
   <text x="${p}" y="${H-8}" font-size="11" fill="var(--muted)">${new Date(xmin).toLocaleDateString("de-DE")}</text>
   <text x="${W-p}" y="${H-8}" font-size="11" fill="var(--muted)" text-anchor="end">${new Date(xmax).toLocaleDateString("de-DE")}</text></svg>`;}
function barChart(pts){const W=600,H=160,p=30;const n=pts.length,ymax=Math.max(...pts.map(o=>o.y),1)*1.1;
 const bw=Math.min(40,(W-2*p)/n-6);let bars="";
 pts.forEach((o,i)=>{const x=p+i*((W-2*p)/n)+((W-2*p)/n-bw)/2;const hgt=(o.y/ymax)*(H-2*p);bars+=`<rect x="${x.toFixed(1)}" y="${(H-p-hgt).toFixed(1)}" width="${bw.toFixed(1)}" height="${hgt.toFixed(1)}" rx="3" fill="var(--mid)"/><text x="${(x+bw/2).toFixed(1)}" y="${H-p-hgt-4}" font-size="10" fill="var(--muted)" text-anchor="middle">${o.y}</text>`;});
 return `<svg width="100%" viewBox="0 0 ${W} ${H}"><line x1="${p}" y1="${H-p}" x2="${W-p}" y2="${H-p}" stroke="var(--line)"/>${bars}</svg>`;}

// ============ BODY SVG ============
function bodySVG(){return `
<svg width="100%" viewBox="0 0 640 405" xmlns="http://www.w3.org/2000/svg" style="color:var(--ink);max-width:430px">
<style>.reg{stroke:currentColor;stroke-opacity:.3;stroke-width:1;fill:var(--none)}.st{fill:var(--none);stroke:currentColor;stroke-opacity:.3;stroke-width:1}
.cp{font-family:"Anton",sans-serif;font-size:12px;letter-spacing:1px;fill:var(--muted);text-anchor:middle}</style>
<text class="cp" x="170" y="22">VORDERSEITE</text>
<circle class="st" cx="170" cy="56" r="18"/><rect class="st" x="162" y="72" width="16" height="12" rx="4"/>
<ellipse class="reg" data-m="shoulders" cx="128" cy="100" rx="21" ry="15"/><ellipse class="reg" data-m="shoulders" cx="212" cy="100" rx="21" ry="15"/>
<path class="reg" data-m="chest" d="M146 92 Q170 88 194 92 Q198 120 170 126 Q142 120 146 92 Z"/>
<ellipse class="reg" data-m="biceps" cx="112" cy="142" rx="12" ry="24"/><ellipse class="reg" data-m="biceps" cx="228" cy="142" rx="12" ry="24"/>
<rect class="st" x="100" y="168" width="17" height="42" rx="8"/><rect class="st" x="223" y="168" width="17" height="42" rx="8"/>
<rect class="reg" data-m="core" x="151" y="128" width="38" height="54" rx="10"/>
<path class="reg" data-m="quads" d="M151 186 Q157 184 166 186 L168 270 Q158 276 151 270 Z"/><path class="reg" data-m="quads" d="M189 186 Q183 184 174 186 L172 270 Q182 276 189 270 Z"/>
<path class="reg" data-m="calves" d="M153 276 L165 276 L162 348 L155 348 Z"/><path class="reg" data-m="calves" d="M187 276 L175 276 L178 348 L185 348 Z"/>
<rect class="st" x="151" y="350" width="17" height="10" rx="3"/><rect class="st" x="172" y="350" width="17" height="10" rx="3"/>
<text class="cp" x="470" y="22">RÜCKSEITE</text>
<circle class="st" cx="470" cy="56" r="18"/><rect class="st" x="462" y="72" width="16" height="12" rx="4"/>
<ellipse class="reg" data-m="shoulders" cx="428" cy="100" rx="21" ry="15"/><ellipse class="reg" data-m="shoulders" cx="512" cy="100" rx="21" ry="15"/>
<path class="reg" data-m="back" d="M446 92 Q470 88 494 92 L498 142 Q470 154 442 142 Z"/>
<ellipse class="reg" data-m="triceps" cx="412" cy="142" rx="12" ry="24"/><ellipse class="reg" data-m="triceps" cx="528" cy="142" rx="12" ry="24"/>
<rect class="st" x="400" y="168" width="17" height="42" rx="8"/><rect class="st" x="523" y="168" width="17" height="42" rx="8"/>
<path class="reg" data-m="lowerback" d="M450 144 L490 144 L486 180 L454 180 Z"/>
<path class="reg" data-m="glutes" d="M448 182 L470 178 L470 216 Q458 222 448 214 Z"/><path class="reg" data-m="glutes" d="M492 182 L470 178 L470 216 Q482 222 492 214 Z"/>
<path class="reg" data-m="hamstrings" d="M450 218 Q456 216 466 218 L468 288 Q458 294 450 288 Z"/><path class="reg" data-m="hamstrings" d="M490 218 Q484 216 474 218 L472 288 Q482 294 490 288 Z"/>
<path class="reg" data-m="calves" d="M452 292 Q458 290 466 292 Q466 330 460 348 Q454 330 452 292 Z"/><path class="reg" data-m="calves" d="M488 292 Q482 290 474 292 Q474 330 480 348 Q486 330 488 292 Z"/>
<rect class="st" x="450" y="350" width="17" height="10" rx="3"/><rect class="st" x="472" y="350" width="17" height="10" rx="3"/></svg>`;}

// ============ CONTROLS / VIEWS ============
function showView(v){document.querySelectorAll(".tab").forEach(t=>t.classList.toggle("on",t.dataset.v===v));
 document.querySelectorAll(".view").forEach(s=>s.classList.remove("on"));document.getElementById("v-"+v).classList.add("on");
 if(v==="hist")renderHist();if(v==="train"){if(!logState&&PLAN)buildLog();else renderTrain();}}
function chip(parent,label,active,on){const b=document.createElement("button");b.className="chip"+(active?" on":"");b.textContent=label;b.onclick=on;parent.appendChild(b);return b;}
function buildControls(){
 const g=document.getElementById("goals");Object.entries(GOALS).forEach(([k,v])=>{const d=document.createElement("div");d.className="goal"+(k===S.goal?" on":"");d.dataset.g=k;
   d.innerHTML=`<h3>${v.label}</h3><p>${v.desc}</p><div class="params">${v.params}</div>`;d.onclick=()=>{S.goal=k;refresh();};g.appendChild(d);});
 const dd=document.getElementById("days");[1,2,3,4,5,6].forEach(n=>{const b=document.createElement("button");b.className="chip day"+(n===S.days?" on":"");b.textContent=n;b.onclick=()=>{S.days=n;refresh();};dd.appendChild(b);});
 const lv=document.getElementById("level");[["beg","Einsteiger"],["int","Geübt"],["adv","Fortgeschritten"]].forEach(([k,t])=>{const b=document.createElement("button");b.className="chip"+(k===S.level?" on":"");b.textContent=t;b.dataset.lv=k;b.onclick=()=>{S.level=k;refresh();};lv.appendChild(b);});
 const sp=document.getElementById("split");[["auto","Automatisch"],["full","Ganzkörper"],["ul","Ober/Unter"],["ppl","Push/Pull/Beine"]].forEach(([k,t])=>{const b=document.createElement("button");b.className="chip"+(k===S.split?" on":"");b.textContent=t;b.dataset.sp=k;b.onclick=()=>{S.split=k;refresh();};sp.appendChild(b);});
 const bl=document.getElementById("block");[4,6].forEach(n=>{const b=document.createElement("button");b.className="chip"+(n===S.block?" on":"");b.textContent=n+" Wochen";b.dataset.bl=n;b.onclick=()=>{S.block=n;refresh();};bl.appendChild(b);});
 const eq=document.getElementById("equip");Object.entries(EQL).forEach(([k,t])=>{const b=document.createElement("button");b.className="chip"+(S.equipSet.has(k)?" on":"");b.textContent=t;b.dataset.eq=k;b.onclick=()=>{if(S.equipSet.has(k)){if(S.equipSet.size>1)S.equipSet.delete(k);}else S.equipSet.add(k);refresh();};eq.appendChild(b);});
}
function refresh(){
 document.querySelectorAll("#goals .goal").forEach(b=>b.classList.toggle("on",b.dataset.g===S.goal));
 document.querySelectorAll("#days .chip").forEach(b=>b.classList.toggle("on",+b.textContent===S.days));
 document.querySelectorAll("#level .chip").forEach(b=>b.classList.toggle("on",b.dataset.lv===S.level));
 document.querySelectorAll("#split .chip").forEach(b=>b.classList.toggle("on",b.dataset.sp===S.split));
 document.querySelectorAll("#block .chip").forEach(b=>b.classList.toggle("on",+b.dataset.bl===S.block));
 document.querySelectorAll("#equip .chip").forEach(b=>b.classList.toggle("on",S.equipSet.has(b.dataset.eq)));
 saveCfg();
}
buildControls();
if(PLAN)renderPlan();
</script>
</body>
</html>
