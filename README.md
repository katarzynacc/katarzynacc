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
| Screen time (Linux) | 24h | 167.8h | 488.4h | ~7098h* |
| Interactive human attention | 2.4h | 29.5h | 107.5h | 188.7h |
| Interactive AI generation | 2.1h | 29.9h | 96.6h | 157.1h |
| Worker-classified human attention | 0.4h | 14.7h | 52.9h | 54.1h |
| Worker/headless AI generation | 8.7h | 116.9h | 718.6h | 917.2h |
| Additive observed work | 13.3h | 186.5h | 961.6h | 1,303.2h |
| Interactive sessions | 3 | 56 | 295 | 524 |
| Worker sessions | 377 | 1,093 | 4,522 | 7,458 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 54 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 87,853 | 93K | 31.9M | 5,545.1M | $2,712.83 | $14,971.98 | $8,573.53 |
| claude-opus-4-6 | 7,463 | 8K | 2.5M | 623.4M | $1,550.84 | $8,416.61 | $0.00 |
| deepseek-v4-flash-free | 18,667 | 44.6M | 3.9M | 1,529.5M | $703.08 | $4,129.82 | $2,610.69 |
| gpt-5.6-sol | 6,997 | 32.3M | 1.4M | 507.0M | $496.92 | $1,369.15 | $1,085.01 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 3,505 | 43K | 1.3M | 235.7M | $188.76 | $636.63 | $363.55 |
| gpt-5.5 | 7,806 | 22.7M | 1.2M | 332.2M | $165.64 | $897.15 | $747.72 |
| claude-haiku-4-5 | 24,326 | 40K | 5.3M | 1,269.7M | $154.77 | $914.23 | $2,180.96 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 271 | 954K | 42K | 11.1M | $6.05 | $30.01 | $27.32 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 932 | 2.3M | 133K | 46.9M | $2.58 | $87.95 | $79.32 |
| **Total** | **176,416** | **120.3M** | **52.7M** | **10,912.6M** | **$6,425.55** | **$33,446.98** | **$17,060.44** |

_11,342.7M total tokens processed. 96.2% cache hit rate._

_$50,507.42 total saved ($33,446.98 caching + $17,060.44 model routing vs all-Opus)._

_Model savings are modest because ~96.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 119,808 | 126K | 45.1M | 7,225.1M | $3,602.39 | $19,507.96 | $11,377.90 |
| claude-opus-4-6 | 7,672 | 8K | 2.6M | 641.4M | $1,597.62 | $8,659.58 | $0.00 |
| deepseek-v4-flash-free | 22,881 | 53.7M | 5.0M | 1,879.9M | $865.03 | $5,076.00 | $3,206.41 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| gpt-5.6-sol | 6,997 | 32.3M | 1.4M | 507.0M | $496.92 | $1,369.15 | $1,085.01 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,363 | 40K | 5.3M | 1,270.8M | $154.99 | $914.98 | $2,182.88 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 271 | 954K | 42K | 11.1M | $6.05 | $30.01 | $27.32 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **240,290** | **158.1M** | **74.7M** | **14,695.5M** | **$9,135.18** | **$46,490.09** | **$22,960.77** |

_15,325.7M total tokens processed. 95.9% cache hit rate._

_$69,450.86 total saved ($46,490.09 caching + $22,960.77 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-21 20:25 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
