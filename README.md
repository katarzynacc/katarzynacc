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
| Screen time (Linux) | 23.9h | 144.1h | 488.3h | ~7032h* |
| Interactive human attention | 5.6h | 24.0h | 103.6h | 175.4h |
| Interactive AI generation | 7.1h | 29.5h | 91.4h | 144.9h |
| Worker-classified human attention | 1.0h | 13.5h | 44.7h | 45.9h |
| Worker/headless AI generation | 18.2h | 271.1h | 740.2h | 885.5h |
| Additive observed work | 31.7h | 336.7h | 969.8h | 1,241.7h |
| Interactive sessions | 21 | 76 | 308 | 508 |
| Worker sessions | 201 | 1,202 | 4,433 | 6,965 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 51 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 90,554 | 95K | 33.0M | 5,441.8M | $2,677.41 | $14,693.10 | $8,516.14 |
| claude-opus-4-6 | 6,946 | 7K | 2.4M | 567.0M | $1,285.50 | $7,655.67 | $0.00 |
| deepseek-v4-flash-free | 18,118 | 43.1M | 3.8M | 1,482.7M | $680.75 | $4,003.44 | $2,528.17 |
| gpt-5.6-sol | 5,911 | 24.3M | 1.1M | 405.7M | $382.94 | $1,095.62 | $849.96 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 5,591 | 67K | 2.2M | 375.0M | $291.69 | $1,012.54 | $587.58 |
| gpt-5.5 | 8,621 | 25.1M | 1.4M | 363.5M | $182.65 | $981.56 | $823.98 |
| claude-haiku-4-5 | 24,325 | 40K | 5.3M | 1,269.7M | $154.75 | $914.23 | $2,180.96 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| claude-opus-4-7 | 137 | 167 | 59K | 6.3M | $21.93 | $85.56 | $0.00 |
| gpt-5.6-terra | 222 | 879K | 41K | 10.9M | $5.81 | $29.58 | $26.20 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 932 | 2.3M | 133K | 46.9M | $2.58 | $87.95 | $79.32 |
| **Total** | **179,953** | **113.2M** | **54.4M** | **10,781.5M** | **$6,130.09** | **$32,552.68** | **$16,984.67** |

_11,204.4M total tokens processed. 96.2% cache hit rate._

_$49,537.34 total saved ($32,552.68 caching + $16,984.67 model routing vs all-Opus)._

_Model savings are modest because ~96.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 111,576 | 117K | 41.8M | 6,486.6M | $3,250.59 | $17,513.98 | $10,298.22 |
| claude-opus-4-6 | 7,155 | 7K | 2.5M | 585.0M | $1,332.28 | $7,898.64 | $0.00 |
| deepseek-v4-flash-free | 22,318 | 52.2M | 4.9M | 1,832.8M | $842.44 | $4,948.68 | $3,122.91 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| gpt-5.6-sol | 5,911 | 24.3M | 1.1M | 405.7M | $382.94 | $1,095.62 | $849.96 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,362 | 40K | 5.3M | 1,270.8M | $154.98 | $914.98 | $2,182.88 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 222 | 879K | 41K | 10.9M | $5.81 | $29.58 | $26.20 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **229,842** | **148.5M** | **70.9M** | **13,752.0M** | **$8,381.22** | **$43,333.89** | **$21,561.42** |

_14,337.8M total tokens processed. 95.9% cache hit rate._

_$64,895.31 total saved ($43,333.89 caching + $21,561.42 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-18 17:09 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
