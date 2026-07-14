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
| Screen time (Linux) | 0h | 24.2h | 439.9h | ~6910h* |
| Interactive human attention | 1.4h | 17.8h | 102.0h | 160.6h |
| Interactive AI generation | 2.7h | 19.2h | 87.1h | 129.9h |
| Worker-classified human attention | 5.5h | 14.1h | 43.7h | 45.0h |
| Worker/headless AI generation | 37.3h | 299.0h | 717.5h | 837.6h |
| Additive observed work | 46.6h | 348.6h | 940.5h | 1,163.3h |
| Interactive sessions | 5 | 50 | 293 | 473 |
| Worker sessions | 123 | 1,277 | 4,227 | 6,494 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok, stale. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 48 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 79,860 | 84K | 28.9M | 4,531.9M | $2,258.41 | $12,236.26 | $7,178.75 |
| claude-opus-4-6 | 5,383 | 5K | 1.8M | 429.6M | $983.35 | $5,800.35 | $0.00 |
| deepseek-v4-flash-free | 16,917 | 42.1M | 3.8M | 1,355.8M | $636.85 | $3,660.90 | $2,362.42 |
| claude-sonnet-4-5 | 6,577 | 76K | 2.7M | 457.3M | $341.30 | $1,234.87 | $713.81 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| gpt-5.5 | 10,430 | 29.7M | 1.7M | 444.7M | $220.93 | $1,200.90 | $996.97 |
| gpt-5.4 | 6,300 | 23.2M | 1.4M | 324.7M | $172.25 | $609.00 | $669.51 |
| gpt-5.6-sol | 2,723 | 10.4M | 487K | 178.1M | $159.85 | $481.08 | $368.25 |
| claude-haiku-4-5 | 24,129 | 38K | 5.2M | 1,261.3M | $153.73 | $908.16 | $2,166.69 |
| claude-opus-4-7 | 137 | 167 | 59K | 6.3M | $21.93 | $85.56 | $0.00 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.5-fast | 183 | 1.0M | 44K | 22.3M | $9.17 | $60.30 | $42.64 |
| claude-sonnet-4-0 | 241 | 1K | 48K | 15.1M | $8.57 | $40.77 | $21.05 |
| gpt-5.6-terra | 187 | 754K | 34K | 8.9M | $4.85 | $24.24 | $21.91 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,107 | 4.2M | 142K | 47.4M | $3.10 | $88.96 | $103.34 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **168,627** | **113.3M** | **50.2M** | **9,658.4M** | **$5,307.16** | **$28,007.30** | **$15,561.50** |

_10,057.7M total tokens processed. 96% cache hit rate._

_$43,568.80 total saved ($28,007.30 caching + $15,561.50 model routing vs all-Opus)._

_Model savings are modest because ~96% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 98,408 | 103K | 36.8M | 5,444.4M | $2,762.36 | $14,699.94 | $8,745.54 |
| claude-opus-4-6 | 5,383 | 5K | 1.8M | 429.6M | $983.35 | $5,800.35 | $0.00 |
| deepseek-v4-flash-free | 19,122 | 47.6M | 4.4M | 1,535.1M | $722.99 | $4,144.78 | $2,677.93 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,698 | 77K | 2.7M | 466.5M | $347.72 | $1,259.70 | $727.88 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| gpt-5.6-sol | 2,723 | 10.4M | 487K | 178.1M | $159.85 | $481.08 | $368.25 |
| claude-haiku-4-5 | 24,166 | 39K | 5.2M | 1,262.3M | $153.95 | $908.91 | $2,168.62 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 187 | 754K | 34K | 8.9M | $4.85 | $24.24 | $21.91 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **208,193** | **129.9M** | **63.9M** | **12,013.0M** | **$7,195.63** | **$36,976.71** | **$19,055.47** |

_12,542.4M total tokens processed. 95.8% cache hit rate._

_$56,032.18 total saved ($36,976.71 caching + $19,055.47 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-14 22:08 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
