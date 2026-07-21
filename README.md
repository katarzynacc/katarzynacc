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
| Interactive sessions | 2 | 55 | 294 | 523 |
| Worker sessions | 154 | 871 | 4,300 | 7,236 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 54 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 93,413 | 98K | 34.3M | 5,855.0M | $2,863.95 | $15,808.57 | $9,086.00 |
| claude-opus-4-6 | 7,436 | 7K | 2.5M | 623.0M | $1,545.50 | $8,410.94 | $0.00 |
| deepseek-v4-flash-free | 18,681 | 44.6M | 3.9M | 1,529.9M | $703.35 | $4,130.75 | $2,611.66 |
| gpt-5.6-sol | 5,913 | 24.3M | 1.1M | 405.7M | $382.94 | $1,095.62 | $849.96 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 3,719 | 45K | 1.4M | 251.0M | $200.49 | $677.81 | $387.76 |
| gpt-5.5 | 7,806 | 22.7M | 1.2M | 332.2M | $165.64 | $897.15 | $747.72 |
| claude-haiku-4-5 | 24,326 | 40K | 5.3M | 1,269.7M | $154.77 | $914.23 | $2,180.96 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| claude-opus-4-7 | 93 | 113 | 40K | 4.2M | $15.22 | $58.00 | $0.00 |
| gpt-5.6-terra | 230 | 879K | 41K | 10.9M | $5.81 | $29.58 | $26.20 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 932 | 2.3M | 133K | 46.9M | $2.58 | $87.95 | $79.32 |
| **Total** | **181,145** | **112.3M** | **54.9M** | **11,140.4M** | **$6,484.33** | **$34,104.03** | **$17,361.94** |

_11,572.4M total tokens processed. 96.3% cache hit rate._

_$51,465.98 total saved ($34,104.03 caching + $17,361.94 model routing vs all-Opus)._

_Model savings are modest because ~96.3% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 119,022 | 126K | 44.8M | 7,146.4M | $3,560.91 | $19,295.33 | $11,267.57 |
| claude-opus-4-6 | 7,645 | 8K | 2.6M | 641.0M | $1,592.27 | $8,653.90 | $0.00 |
| deepseek-v4-flash-free | 22,881 | 53.7M | 5.0M | 1,879.9M | $865.03 | $5,076.00 | $3,206.41 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| gpt-5.6-sol | 5,913 | 24.3M | 1.1M | 405.7M | $382.94 | $1,095.62 | $849.96 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,363 | 40K | 5.3M | 1,270.8M | $154.99 | $914.98 | $2,182.88 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 230 | 879K | 41K | 10.9M | $5.81 | $29.58 | $26.20 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **238,352** | **150.0M** | **74.2M** | **14,514.8M** | **$8,974.13** | **$45,997.82** | **$22,614.27** |

_15,132.4M total tokens processed. 95.9% cache hit rate._

_$68,612.09 total saved ($45,997.82 caching + $22,614.27 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-21 02:25 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
