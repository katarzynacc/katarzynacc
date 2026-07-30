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
| Screen time (Linux) | 24h | 167.8h | 488.5h | ~7269h* |
| Interactive human attention | 0.4h | 11.2h | 18.4h | 127.4h |
| Interactive AI generation | 8.9h | 22.5h | 25.7h | 105.1h |
| Worker-classified human attention | 0.0h | 0.2h | 1.4h | 25.0h |
| Worker/headless AI generation | 3.4h | 44.8h | 703.3h | 1047.2h |
| Additive observed work | 12.7h | 78.6h | 748.2h | 1,298.8h |
| Interactive sessions | 20 | 30 | 48 | 390 |
| Worker sessions | 365 | 1,355 | 4,815 | 8,832 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 63 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 94,919 | 101K | 34.1M | 6,571.9M | $3,203.26 | $17,744.19 | $9,936.90 |
| claude-opus-4-6 | 7,925 | 8K | 2.6M | 656.7M | $1,648.80 | $8,866.66 | $0.00 |
| gpt-5.6-sol | 9,699 | 45.9M | 2.0M | 742.8M | $715.91 | $2,005.61 | $1,567.55 |
| deepseek-v4-flash-free | 14,824 | 34.9M | 3.1M | 1,252.5M | $566.81 | $3,381.90 | $2,108.57 |
| claude-sonnet-4-5 | 8,447 | 21K | 2.0M | 330.2M | $180.94 | $891.66 | $518.75 |
| claude-sonnet-4-5 | 2,766 | 33K | 1.0M | 192.2M | $153.75 | $519.15 | $293.74 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 5,140 | 14.3M | 820K | 211.0M | $105.29 | $569.88 | $474.84 |
| gpt-5.6-terra | 991 | 3.5M | 80K | 23.3M | $16.51 | $63.16 | $75.68 |
| claude-haiku-4-5 | 2,075 | 4K | 415K | 116.2M | $13.49 | $83.68 | $194.61 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 751 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **151,751** | **117.6M** | **47.5M** | **10,373.9M** | **$6,732.46** | **$34,644.67** | **$15,720.92** |

_10,793.2M total tokens processed. 96.1% cache hit rate._

_$50,365.60 total saved ($34,644.67 caching + $15,720.92 model routing vs all-Opus)._

_Model savings are modest because ~96.1% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 133,117 | 141K | 49.6M | 8,627.5M | $4,274.17 | $23,294.32 | $13,336.44 |
| claude-opus-4-6 | 8,186 | 8K | 2.7M | 680.1M | $1,709.34 | $9,182.17 | $0.00 |
| deepseek-v4-flash-free | 23,861 | 55.5M | 5.2M | 1,966.0M | $901.58 | $5,308.40 | $3,344.25 |
| gpt-5.6-sol | 9,699 | 45.9M | 2.0M | 742.8M | $715.91 | $2,005.61 | $1,567.55 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,428 | 40K | 5.3M | 1,273.5M | $155.42 | $916.96 | $2,187.56 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| gpt-5.6-terra | 991 | 3.5M | 80K | 23.3M | $16.51 | $63.16 | $75.68 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **258,580** | **176.2M** | **80.3M** | **16,473.3M** | **$10,185.11** | **$51,703.03** | **$25,592.73** |

_17,178.3M total tokens processed. 95.9% cache hit rate._

_$77,295.76 total saved ($51,703.03 caching + $25,592.73 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-30 18:01 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
