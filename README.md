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
| Screen time (Linux) | 7h | 11.7h | 70.4h | ~1,351h* |
| User AI session hours | 3.8h | 41.4h | 109.5h | 148.0h |
| AI worker hours | 42.8h | 211.0h | 476.5h | 562.3h |
| AI concurrency hours | 50.6h | 287.2h | 664.5h | 820.9h |
| Interactive sessions | 15 | 93 | 254 | 339 |
| Worker sessions | 57 | 202 | 522 | 823 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 39 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 43,117 | 45K | 16.2M | 2,283.0M | $1,172.98 | $6,164.32 | $3,716.11 |
| deepseek-v4-flash-free | 14,576 | 36.3M | 3.4M | 1,162.3M | $552.34 | $3,138.34 | $2,037.62 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-6 | 1,892 | 2K | 767K | 137.2M | $347.59 | $1,853.02 | $0.00 |
| claude-sonnet-4-5 | 5,573 | 63K | 2.4M | 385.1M | $288.85 | $1,039.99 | $607.05 |
| gpt-5.5 | 10,643 | 30.3M | 1.8M | 453.2M | $225.73 | $1,223.66 | $1,018.14 |
| claude-opus-4-0 | 947 | 9K | 246K | 64.8M | $194.04 | $875.19 | $0.00 |
| claude-haiku-4-5 | 23,871 | 37K | 5.2M | 1,241.5M | $151.59 | $893.89 | $2,133.66 |
| claude-sonnet-4-0 | 2,935 | 29K | 850K | 184.8M | $118.63 | $499.13 | $273.25 |
| gpt-5.4 | 4,223 | 15.4M | 884K | 193.9M | $107.72 | $363.74 | $420.11 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.5-fast | 187 | 1.0M | 44K | 22.3M | $9.17 | $60.30 | $42.64 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **125,805** | **88.9M** | **36.2M** | **6,843.1M** | **$3,577.56** | **$18,103.53** | **$11,406.72** |

_7,153.0M total tokens processed. 95.7% cache hit rate._

_$29,510.25 total saved ($18,103.53 caching + $11,406.72 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 56,622 | 59K | 22.1M | 2,950.6M | $1,545.84 | $7,966.87 | $4,873.42 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 14,936 | 37.1M | 3.5M | 1,188.4M | $565.00 | $3,208.79 | $2,084.51 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-6 | 1,892 | 2K | 767K | 137.2M | $347.59 | $1,853.02 | $0.00 |
| claude-sonnet-4-5 | 5,694 | 64K | 2.4M | 394.3M | $295.26 | $1,064.82 | $621.12 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-haiku-4-5 | 23,903 | 37K | 5.2M | 1,242.5M | $151.75 | $894.63 | $2,135.55 |
| gpt-5.4 | 4,420 | 15.9M | 920K | 205.0M | $112.76 | $384.49 | $439.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **151,790** | **97.2M** | **45.8M** | **8,440.5M** | **$4,887.69** | **$24,344.86** | **$13,740.25** |

_8,839.3M total tokens processed. 95.5% cache hit rate._

_$38,085.11 total saved ($24,344.86 caching + $13,740.25 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-07 17:58 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
