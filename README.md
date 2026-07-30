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
| Interactive sessions | 18 | 28 | 46 | 388 |
| Worker sessions | 279 | 1,269 | 4,729 | 8,746 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 63 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 93,788 | 100K | 33.7M | 6,469.6M | $3,152.71 | $17,468.16 | $9,788.93 |
| claude-opus-4-6 | 7,769 | 8K | 2.6M | 646.1M | $1,623.27 | $8,722.86 | $0.00 |
| gpt-5.6-sol | 9,699 | 45.9M | 2.0M | 742.8M | $715.91 | $2,005.61 | $1,567.55 |
| deepseek-v4-flash-free | 15,356 | 36.1M | 3.2M | 1,295.3M | $586.14 | $3,497.36 | $2,181.18 |
| claude-sonnet-4-5 | 8,896 | 23K | 2.1M | 346.2M | $189.97 | $934.85 | $543.50 |
| claude-sonnet-4-5 | 2,766 | 33K | 1.0M | 192.2M | $153.75 | $519.15 | $293.74 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 5,685 | 16.0M | 899K | 227.5M | $115.33 | $614.41 | $519.97 |
| gpt-5.6-terra | 946 | 3.4M | 79K | 22.7M | $16.17 | $61.52 | $74.07 |
| claude-haiku-4-5 | 2,036 | 4K | 408K | 114.1M | $13.20 | $82.20 | $191.19 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 751 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **151,906** | **120.4M** | **47.3M** | **10,333.6M** | **$6,694.15** | **$34,424.88** | **$15,710.40** |

_10,752.2M total tokens processed. 96.1% cache hit rate._

_$50,135.28 total saved ($34,424.88 caching + $15,710.40 model routing vs all-Opus)._

_Model savings are modest because ~96.1% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 131,986 | 140K | 49.2M | 8,525.2M | $4,223.62 | $23,018.29 | $13,188.47 |
| claude-opus-4-6 | 8,030 | 8K | 2.7M | 669.5M | $1,683.81 | $9,038.36 | $0.00 |
| deepseek-v4-flash-free | 23,861 | 55.5M | 5.2M | 1,966.0M | $901.58 | $5,308.40 | $3,344.25 |
| gpt-5.6-sol | 9,699 | 45.9M | 2.0M | 742.8M | $715.91 | $2,005.61 | $1,567.55 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,389 | 40K | 5.3M | 1,271.4M | $155.13 | $915.47 | $2,184.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| gpt-5.6-terra | 946 | 3.4M | 79K | 22.7M | $16.17 | $61.52 | $74.07 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **257,209** | **176.1M** | **79.9M** | **16,357.8M** | **$10,108.40** | **$51,280.06** | **$25,439.72** |

_17,058.1M total tokens processed. 95.9% cache hit rate._

_$76,719.78 total saved ($51,280.06 caching + $25,439.72 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-30 09:01 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
