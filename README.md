# Kasia CC

![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
>
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 1h | 59.9h | 84.2h | ~1,351h* |
| User AI session hours | 6.6h | 36.4h | 107.9h | 123.2h |
| AI worker hours | 44.5h | 177.2h | 379.9h | 436.4h |
| AI concurrency hours | 53.9h | 235.9h | 557.0h | 644.4h |
| Interactive sessions | 17 | 118 | 258 | 290 |
| Worker sessions | 31 | 161 | 519 | 688 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 35 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 32,195 | 33K | 12.5M | 1,793.0M | $904.72 | $4,841.13 | $2,904.59 |
| claude-opus-4-0 | 2,800 | 26K | 776K | 216.6M | $622.44 | $2,925.02 | $0.00 |
| deepseek-v4-flash-free | 11,554 | 27.3M | 2.7M | 915.1M | $431.96 | $2,471.01 | $1,591.62 |
| claude-sonnet-4-5 | 11,763 | 32K | 2.8M | 464.5M | $262.60 | $1,254.38 | $730.83 |
| claude-sonnet-4-5 | 4,694 | 53K | 2.1M | 326.2M | $242.49 | $880.84 | $518.71 |
| claude-sonnet-4-0 | 5,406 | 54K | 1.6M | 378.2M | $239.15 | $1,021.15 | $554.52 |
| gpt-5.5 | 10,559 | 31.3M | 1.8M | 478.4M | $234.64 | $1,291.82 | $1,060.75 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 468 | 527 | 201K | 43.9M | $104.76 | $593.93 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 734 | 4.5M | 67K | 22.2M | $2.14 | $41.74 | $80.49 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **105,968** | **75.7M** | **30.4M** | **5,973.3M** | **$3,308.72** | **$16,631.41** | **$9,790.99** |

_6,249.7M total tokens processed. 95.6% cache hit rate._

_$26,422.40 total saved ($16,631.41 caching + $9,790.99 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 41,023 | 43K | 16.4M | 2,219.5M | $1,147.18 | $5,992.88 | $3,650.10 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 11,554 | 27.3M | 2.7M | 915.1M | $431.96 | $2,471.01 | $1,591.62 |
| claude-sonnet-4-5 | 11,763 | 32K | 2.8M | 464.5M | $262.60 | $1,254.38 | $730.83 |
| claude-sonnet-4-5 | 4,694 | 53K | 2.1M | 326.2M | $242.49 | $880.84 | $518.71 |
| gpt-5.5 | 10,559 | 31.3M | 1.8M | 478.4M | $234.64 | $1,291.82 | $1,060.75 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 468 | 527 | 201K | 43.9M | $104.76 | $593.93 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 734 | 4.5M | 67K | 22.2M | $2.14 | $41.74 | $80.49 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **120,398** | **75.8M** | **36.0M** | **6,822.2M** | **$3,862.77** | **$19,223.23** | **$11,109.81** |

_7,145.3M total tokens processed. 95.5% cache hit rate._

_$30,333.04 total saved ($19,223.23 caching + $11,109.81 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-03 16:15 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
