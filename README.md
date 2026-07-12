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
| Screen time (Linux) | 22.6h | 60.1h | 508.9h | ~7002h* |
| Interactive human attention | 2.0h | 27.2h | 101.9h | 153.5h |
| Interactive AI generation | 4.1h | 20.3h | 81.2h | 119.6h |
| Worker-classified human attention | 2.4h | 6.9h | 33.6h | 34.8h |
| Worker/headless AI generation | 97.8h | 281.4h | 605.1h | 712.1h |
| Additive observed work | 106.1h | 334.4h | 813.0h | 1,011.1h |
| Interactive sessions | 20 | 79 | 306 | 452 |
| Worker sessions | 387 | 1,639 | 4,274 | 6,159 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 45 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 66,627 | 70K | 24.6M | 3,538.0M | $1,819.82 | $9,552.86 | $5,725.58 |
| deepseek-v4-flash-free | 15,813 | 40.1M | 3.6M | 1,269.7M | $599.69 | $3,428.32 | $2,222.81 |
| claude-opus-4-6 | 2,275 | 2K | 915K | 158.7M | $411.66 | $2,142.98 | $0.00 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 5,833 | 66K | 2.4M | 400.6M | $300.61 | $1,081.69 | $631.42 |
| gpt-5.5 | 10,624 | 30.3M | 1.8M | 453.1M | $225.73 | $1,223.63 | $1,018.13 |
| gpt-5.4 | 6,724 | 24.7M | 1.5M | 344.2M | $182.56 | $645.53 | $709.14 |
| claude-haiku-4-5 | 24,129 | 38K | 5.2M | 1,261.3M | $153.73 | $908.16 | $2,166.69 |
| gpt-5.6-sol | 1,221 | 4.5M | 207K | 52.9M | $57.29 | $143.09 | $130.64 |
| claude-opus-4-7 | 137 | 167 | 59K | 6.3M | $21.93 | $85.56 | $0.00 |
| claude-sonnet-4-0 | 477 | 4K | 117K | 29.6M | $19.15 | $80.18 | $42.72 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.5-fast | 183 | 1.0M | 44K | 22.3M | $9.17 | $60.30 | $42.64 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| gpt-5.6-terra | 139 | 484K | 27K | 6.4M | $3.37 | $17.28 | $15.14 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **149,888** | **108.7M** | **44.5M** | **8,165.9M** | **$4,141.14** | **$21,035.23** | **$13,745.15** |

_8,525.7M total tokens processed. 95.8% cache hit rate._

_$34,780.38 total saved ($21,035.23 caching + $13,745.15 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 84,286 | 89K | 32.1M | 4,408.7M | $2,300.74 | $11,903.49 | $7,222.25 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 18,018 | 45.6M | 4.1M | 1,448.9M | $685.83 | $3,912.20 | $2,538.31 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-opus-4-6 | 2,275 | 2K | 915K | 158.7M | $411.66 | $2,142.98 | $0.00 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,954 | 67K | 2.5M | 409.8M | $307.02 | $1,106.52 | $645.49 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,166 | 39K | 5.2M | 1,262.3M | $153.95 | $908.91 | $2,168.62 |
| gpt-5.6-sol | 1,221 | 4.5M | 207K | 52.9M | $57.29 | $143.09 | $130.64 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| gpt-5.6-terra | 139 | 484K | 27K | 6.4M | $3.37 | $17.28 | $15.14 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **187,565** | **121.7M** | **57.6M** | **10,435.7M** | **$5,980.42** | **$29,792.19** | **$17,065.80** |

_10,918.5M total tokens processed. 95.6% cache hit rate._

_$46,857.99 total saved ($29,792.19 caching + $17,065.80 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-12 15:36 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
