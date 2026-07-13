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
| Screen time (Linux) | 1.6h | 61.2h | 486.5h | ~7002h* |
| Interactive human attention | 2.3h | 23.7h | 104.2h | 155.7h |
| Interactive AI generation | 2.8h | 20.5h | 84.0h | 122.4h |
| Worker-classified human attention | 3.6h | 9.6h | 37.2h | 38.4h |
| Worker/headless AI generation | 29.4h | 290.7h | 632.7h | 741.5h |
| Additive observed work | 37.5h | 343.0h | 848.7h | 1,048.6h |
| Interactive sessions | 10 | 63 | 309 | 455 |
| Worker sessions | 136 | 1,550 | 4,323 | 6,226 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 46 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 68,301 | 72K | 25.2M | 3,657.2M | $1,872.44 | $9,874.53 | $5,901.57 |
| deepseek-v4-flash-free | 16,008 | 40.5M | 3.6M | 1,285.6M | $606.10 | $3,471.14 | $2,247.23 |
| claude-opus-4-6 | 2,310 | 2K | 940K | 160.9M | $418.38 | $2,172.54 | $0.00 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 5,833 | 66K | 2.4M | 400.6M | $300.61 | $1,081.69 | $631.42 |
| gpt-5.5 | 10,430 | 29.7M | 1.7M | 444.7M | $220.93 | $1,200.90 | $996.97 |
| gpt-5.4 | 6,482 | 23.8M | 1.4M | 333.5M | $176.62 | $625.40 | $686.26 |
| claude-haiku-4-5 | 24,129 | 38K | 5.2M | 1,261.3M | $153.73 | $908.16 | $2,166.69 |
| gpt-5.6-sol | 2,483 | 9.3M | 441K | 163.0M | $145.00 | $440.25 | $334.04 |
| claude-opus-4-7 | 137 | 167 | 59K | 6.3M | $21.93 | $85.56 | $0.00 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.5-fast | 183 | 1.0M | 44K | 22.3M | $9.17 | $60.30 | $42.64 |
| claude-sonnet-4-0 | 255 | 2K | 50K | 15.2M | $8.88 | $41.26 | $21.37 |
| gpt-5.6-terra | 187 | 754K | 34K | 8.9M | $4.85 | $24.24 | $21.91 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,217 | 5.4M | 148K | 47.7M | $3.45 | $89.48 | $119.13 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **152,408** | **112.2M** | **45.1M** | **8,382.1M** | **$4,274.96** | **$21,651.40** | **$14,085.40** |

_8,747.1M total tokens processed. 95.8% cache hit rate._

_$35,736.79 total saved ($21,651.40 caching + $14,085.40 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 86,801 | 91K | 33.0M | 4,568.7M | $2,375.46 | $12,335.60 | $7,466.16 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 18,213 | 45.9M | 4.2M | 1,464.8M | $692.24 | $3,955.02 | $2,562.74 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-opus-4-6 | 2,310 | 2K | 940K | 160.9M | $418.38 | $2,172.54 | $0.00 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,954 | 67K | 2.5M | 409.8M | $307.02 | $1,106.52 | $645.49 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,166 | 39K | 5.2M | 1,262.3M | $153.95 | $908.91 | $2,168.62 |
| gpt-5.6-sol | 2,483 | 9.3M | 441K | 163.0M | $145.00 | $440.25 | $334.04 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 187 | 754K | 34K | 8.9M | $4.85 | $24.24 | $21.91 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **191,620** | **127.1M** | **58.8M** | **10,726.4M** | **$6,157.46** | **$30,600.79** | **$17,544.31** |

_11,219.5M total tokens processed. 95.6% cache hit rate._

_$48,145.10 total saved ($30,600.79 caching + $17,544.31 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-13 03:30 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
