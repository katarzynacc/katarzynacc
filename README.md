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
| Screen time (Linux) | 24h | 59.9h | 84.2h | ~1,351h* |
| User AI session hours | 6.2h | 37.7h | 110.8h | 128.5h |
| AI worker hours | 15.8h | 159.4h | 382.2h | 447.8h |
| AI concurrency hours | 36.6h | 230.6h | 573.2h | 675.0h |
| Interactive sessions | 7 | 111 | 248 | 294 |
| Worker sessions | 24 | 156 | 501 | 708 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 36 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 32,398 | 34K | 12.3M | 1,798.6M | $903.76 | $4,856.48 | $2,899.73 |
| claude-opus-4-0 | 2,800 | 26K | 776K | 216.6M | $622.44 | $2,925.02 | $0.00 |
| deepseek-v4-flash-free | 12,366 | 29.6M | 2.9M | 987.3M | $465.13 | $2,665.75 | $1,717.05 |
| claude-sonnet-4-5 | 14,411 | 38K | 3.5M | 582.5M | $323.55 | $1,572.98 | $913.00 |
| claude-sonnet-4-5 | 4,718 | 53K | 2.1M | 327.7M | $244.65 | $884.93 | $521.45 |
| gpt-5.5 | 10,575 | 31.4M | 1.8M | 478.8M | $235.05 | $1,292.94 | $1,062.58 |
| claude-sonnet-4-0 | 4,287 | 42K | 1.2M | 286.9M | $180.81 | $774.70 | $421.25 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 468 | 527 | 201K | 43.9M | $104.76 | $593.93 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 734 | 4.5M | 67K | 22.2M | $2.14 | $41.74 | $80.49 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **108,552** | **78.1M** | **30.7M** | **6,079.7M** | **$3,346.11** | **$16,918.87** | **$9,965.04** |

_6,356.8M total tokens processed. 95.6% cache hit rate._

_$26,883.90 total saved ($16,918.87 caching + $9,965.04 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 43,252 | 45K | 17.1M | 2,317.9M | $1,199.96 | $6,258.48 | $3,809.94 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 12,366 | 29.6M | 2.9M | 987.3M | $465.13 | $2,665.75 | $1,717.05 |
| claude-sonnet-4-5 | 14,411 | 38K | 3.5M | 582.5M | $323.55 | $1,572.98 | $913.00 |
| claude-sonnet-4-5 | 4,718 | 53K | 2.1M | 327.7M | $244.65 | $884.93 | $521.45 |
| gpt-5.5 | 10,575 | 31.4M | 1.8M | 478.8M | $235.05 | $1,292.94 | $1,062.58 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 468 | 527 | 201K | 43.9M | $104.76 | $593.93 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 734 | 4.5M | 67K | 22.2M | $2.14 | $41.74 | $80.49 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **126,127** | **78.2M** | **37.6M** | **7,112.7M** | **$4,012.24** | **$20,007.38** | **$11,581.84** |

_7,447.7M total tokens processed. 95.5% cache hit rate._

_$31,589.22 total saved ($20,007.38 caching + $11,581.84 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-04 13:19 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
