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
| Interactive sessions | 13 | 70 | 298 | 494 |
| Worker sessions | 172 | 1,473 | 4,333 | 6,838 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 50 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 86,374 | 91K | 31.3M | 5,006.6M | $2,474.26 | $13,517.86 | $7,891.81 |
| claude-opus-4-6 | 6,136 | 6K | 2.0M | 498.1M | $1,126.95 | $6,724.38 | $0.00 |
| deepseek-v4-flash-free | 18,254 | 43.5M | 3.9M | 1,489.6M | $685.28 | $4,022.13 | $2,544.65 |
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
| **Total** | **177,667** | **116.9M** | **53.1M** | **10,425.0M** | **$5,848.28** | **$30,870.73** | **$16,619.96** |

_10,841.7M total tokens processed. 96.2% cache hit rate._

_$47,490.68 total saved ($30,870.73 caching + $16,619.96 model routing vs all-Opus)._

_Model savings are modest because ~96.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 106,509 | 112K | 39.8M | 6,012.7M | $3,025.19 | $16,234.45 | $9,606.94 |
| claude-opus-4-6 | 6,345 | 6K | 2.1M | 516.0M | $1,173.73 | $6,967.35 | $0.00 |
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
| **Total** | **222,931** | **146.0M** | **68.3M** | **13,125.3M** | **$7,947.28** | **$40,908.02** | **$20,724.21** |

_13,690.3M total tokens processed. 95.9% cache hit rate._

_$61,632.23 total saved ($40,908.02 caching + $20,724.21 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-17 13:30 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
