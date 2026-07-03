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
| User AI session hours | 6.2h | 36.1h | 108.6h | 125.1h |
| AI worker hours | 44.2h | 179.0h | 393.3h | 450.7h |
| AI concurrency hours | 53.2h | 237.0h | 569.8h | 661.3h |
| Interactive sessions | 14 | 113 | 248 | 291 |
| Worker sessions | 34 | 155 | 521 | 697 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 36 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 33,216 | 35K | 12.7M | 1,838.7M | $927.03 | $4,964.52 | $2,974.28 |
| claude-opus-4-0 | 2,800 | 26K | 776K | 216.6M | $622.44 | $2,925.02 | $0.00 |
| deepseek-v4-flash-free | 11,730 | 28.3M | 2.8M | 930.5M | $441.00 | $2,512.49 | $1,625.70 |
| claude-sonnet-4-5 | 12,902 | 35K | 3.1M | 519.9M | $289.12 | $1,403.84 | $814.14 |
| claude-sonnet-4-5 | 4,718 | 53K | 2.1M | 327.7M | $244.65 | $884.93 | $521.45 |
| gpt-5.5 | 10,559 | 31.3M | 1.8M | 478.4M | $234.64 | $1,291.82 | $1,060.75 |
| claude-sonnet-4-0 | 5,187 | 52K | 1.6M | 359.3M | $226.17 | $970.32 | $528.19 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 468 | 527 | 201K | 43.9M | $104.76 | $593.93 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 734 | 4.5M | 67K | 22.2M | $2.14 | $41.74 | $80.49 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **108,109** | **76.8M** | **30.9M** | **6,072.4M** | **$3,355.77** | **$16,899.01** | **$9,954.48** |

_6,351.9M total tokens processed. 95.6% cache hit rate._

_$26,853.49 total saved ($16,899.01 caching + $9,954.48 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 42,758 | 45K | 16.9M | 2,296.5M | $1,187.88 | $6,200.80 | $3,775.28 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 11,730 | 28.3M | 2.8M | 930.5M | $441.00 | $2,512.49 | $1,625.70 |
| claude-sonnet-4-5 | 12,902 | 35K | 3.1M | 519.9M | $289.12 | $1,403.84 | $814.14 |
| claude-sonnet-4-5 | 4,718 | 53K | 2.1M | 327.7M | $244.65 | $884.93 | $521.45 |
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
| **Total** | **123,472** | **76.9M** | **36.9M** | **6,971.5M** | **$3,941.19** | **$19,626.18** | **$11,355.13** |

_7,300.9M total tokens processed. 95.5% cache hit rate._

_$30,981.31 total saved ($19,626.18 caching + $11,355.13 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-03 23:19 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
