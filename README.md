# Kasia CC

![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
>
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | Yesterday | Prior 7 Days | Prior 28 Days | Prior 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 24h | 120.2h | 488.3h | ~7010h* |
| Interactive human attention | 2.6h | 25.0h | 100.3h | 169.8h |
| Interactive AI generation | 2.8h | 26.4h | 85.4h | 137.8h |
| Worker-classified human attention | 0.0h | 13.7h | 43.7h | 45.0h |
| Worker/headless AI generation | 11.1h | 309.6h | 722.9h | 867.0h |
| Additive observed work | 16.5h | 373.4h | 942.5h | 1,209.8h |
| Interactive sessions | 14 | 71 | 299 | 495 |
| Worker sessions | 176 | 1,477 | 4,337 | 6,842 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 50 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 86,609 | 91K | 31.4M | 5,028.0M | $2,483.51 | $13,575.77 | $7,922.11 |
| claude-opus-4-6 | 6,162 | 6K | 2.1M | 499.0M | $1,130.02 | $6,737.82 | $0.00 |
| deepseek-v4-flash-free | 18,234 | 43.4M | 3.9M | 1,488.9M | $684.79 | $4,020.27 | $2,542.85 |
| gpt-5.6-sol | 5,456 | 22.6M | 1.0M | 370.1M | $351.02 | $999.52 | $779.23 |
| claude-sonnet-4-5 | 6,671 | 77K | 2.7M | 462.9M | $345.20 | $1,249.87 | $721.83 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| gpt-5.5 | 10,394 | 29.6M | 1.7M | 444.2M | $220.26 | $1,199.34 | $993.92 |
| claude-haiku-4-5 | 24,210 | 39K | 5.2M | 1,264.1M | $154.09 | $910.19 | $2,171.54 |
| gpt-5.4 | 4,465 | 16.4M | 1.1M | 252.6M | $128.99 | $473.70 | $499.40 |
| claude-opus-4-7 | 137 | 167 | 59K | 6.3M | $21.93 | $85.56 | $0.00 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 189 | 770K | 34K | 8.9M | $4.90 | $24.28 | $22.13 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 932 | 2.3M | 133K | 46.9M | $2.58 | $87.95 | $79.32 |
| **Total** | **177,908** | **116.9M** | **53.2M** | **10,446.8M** | **$5,860.11** | **$30,940.21** | **$16,648.46** |

_10,864.0M total tokens processed. 96.2% cache hit rate._

_$47,588.67 total saved ($30,940.21 caching + $16,648.46 model routing vs all-Opus)._

_Model savings are modest because ~96.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 106,750 | 112K | 39.9M | 6,034.2M | $3,034.75 | $16,292.43 | $9,637.33 |
| claude-opus-4-6 | 6,371 | 6K | 2.1M | 517.0M | $1,176.80 | $6,980.79 | $0.00 |
| deepseek-v4-flash-free | 21,887 | 51.4M | 4.8M | 1,792.2M | $825.95 | $4,839.08 | $3,061.20 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.6-sol | 5,456 | 22.6M | 1.0M | 370.1M | $351.02 | $999.52 | $779.23 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,247 | 39K | 5.3M | 1,265.1M | $154.31 | $910.94 | $2,173.47 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 189 | 770K | 34K | 8.9M | $4.90 | $24.28 | $22.13 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **223,198** | **146.0M** | **68.4M** | **13,147.8M** | **$7,959.91** | **$40,979.44** | **$20,754.60** |

_13,713.4M total tokens processed. 95.9% cache hit rate._

_$61,734.04 total saved ($40,979.44 caching + $20,754.60 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-17 15:30 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
