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
| Screen time (Linux) | 23.9h | 96.2h | 488.3h | ~6986h* |
| Interactive human attention | 6.5h | 23.6h | 103.1h | 167.2h |
| Interactive AI generation | 5.1h | 24.0h | 88.1h | 135.0h |
| Worker-classified human attention | 0.0h | 13.8h | 43.7h | 45.0h |
| Worker/headless AI generation | 18.3h | 306.1h | 722.8h | 856.0h |
| Additive observed work | 29.9h | 366.1h | 948.0h | 1,193.4h |
| Interactive sessions | 16 | 64 | 300 | 488 |
| Worker sessions | 278 | 1,474 | 4,363 | 6,767 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 49 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 83,778 | 88K | 30.4M | 4,861.9M | $2,404.71 | $13,127.25 | $7,663.62 |
| claude-opus-4-6 | 5,845 | 6K | 1.9M | 480.7M | $1,082.80 | $6,490.16 | $0.00 |
| deepseek-v4-flash-free | 17,461 | 42.1M | 3.7M | 1,413.8M | $654.76 | $3,817.39 | $2,430.52 |
| gpt-5.6-sol | 5,456 | 22.6M | 1.0M | 370.1M | $351.02 | $999.52 | $779.23 |
| claude-sonnet-4-5 | 6,671 | 77K | 2.7M | 462.9M | $345.20 | $1,249.87 | $721.83 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| gpt-5.5 | 10,395 | 29.6M | 1.7M | 444.2M | $220.27 | $1,199.36 | $993.99 |
| claude-haiku-4-5 | 24,129 | 38K | 5.2M | 1,261.3M | $153.73 | $908.16 | $2,166.69 |
| gpt-5.4 | 4,652 | 17.0M | 1.1M | 259.2M | $132.92 | $486.13 | $514.75 |
| claude-opus-4-7 | 137 | 167 | 59K | 6.3M | $21.93 | $85.56 | $0.00 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 189 | 770K | 34K | 8.9M | $4.90 | $24.28 | $22.13 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.5-fast | 61 | 456K | 15K | 5.5M | $2.83 | $15.10 | $13.13 |
| gpt-5.4-mini | 953 | 2.6M | 134K | 46.9M | $2.65 | $88.04 | $82.40 |
| **Total** | **174,176** | **116.9M** | **52.0M** | **10,196.6M** | **$5,710.54** | **$30,066.75** | **$16,304.43** |

_10,608.2M total tokens processed. 96.1% cache hit rate._

_$46,371.17 total saved ($30,066.75 caching + $16,304.43 model routing vs all-Opus)._

_Model savings are modest because ~96.1% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 103,554 | 109K | 38.8M | 5,835.1M | $2,941.28 | $15,754.82 | $9,331.68 |
| claude-opus-4-6 | 6,054 | 6K | 2.0M | 498.7M | $1,129.58 | $6,733.13 | $0.00 |
| deepseek-v4-flash-free | 20,668 | 49.5M | 4.6M | 1,677.5M | $779.22 | $4,529.51 | $2,887.45 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.6-sol | 5,456 | 22.6M | 1.0M | 370.1M | $351.02 | $999.52 | $779.23 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,166 | 39K | 5.2M | 1,262.3M | $153.95 | $908.91 | $2,168.62 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 189 | 770K | 34K | 8.9M | $4.90 | $24.28 | $22.13 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **218,385** | **144.0M** | **67.0M** | **12,812.9M** | **$7,772.13** | **$39,882.58** | **$20,270.35** |

_13,369.9M total tokens processed. 95.8% cache hit rate._

_$60,152.93 total saved ($39,882.58 caching + $20,270.35 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-16 21:34 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
