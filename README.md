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
| Screen time (Linux) | 4.7h | 59.9h | 84.2h | ~1,351h* |
| User AI session hours | 6.1h | 36.3h | 107.8h | 122.2h |
| AI worker hours | 41.2h | 182.9h | 375.4h | 431.9h |
| AI concurrency hours | 49.7h | 240.8h | 552.7h | 638.1h |
| Interactive sessions | 17 | 116 | 257 | 288 |
| Worker sessions | 32 | 164 | 519 | 685 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 35 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 31,987 | 33K | 12.4M | 1,777.6M | $898.27 | $4,799.62 | $2,881.92 |
| claude-opus-4-0 | 2,800 | 26K | 776K | 216.6M | $622.44 | $2,925.02 | $0.00 |
| deepseek-v4-flash-free | 11,554 | 27.3M | 2.7M | 915.1M | $431.96 | $2,471.01 | $1,591.62 |
| claude-sonnet-4-5 | 11,497 | 32K | 2.8M | 453.5M | $256.57 | $1,224.56 | $713.32 |
| claude-sonnet-4-0 | 5,688 | 57K | 1.7M | 393.2M | $249.98 | $1,061.71 | $576.95 |
| gpt-5.5 | 10,538 | 31.2M | 1.8M | 475.8M | $233.74 | $1,284.91 | $1,056.52 |
| claude-sonnet-4-5 | 4,501 | 50K | 1.9M | 311.9M | $226.43 | $842.23 | $494.67 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 468 | 527 | 201K | 43.9M | $104.76 | $593.93 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 712 | 4.5M | 65K | 19.9M | $2.06 | $37.36 | $77.97 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **105,540** | **75.6M** | **30.2M** | **5,942.7M** | **$3,290.03** | **$16,550.76** | **$9,742.45** |

_6,217.0M total tokens processed. 95.6% cache hit rate._

_$26,293.21 total saved ($16,550.76 caching + $9,742.45 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 40,786 | 43K | 16.3M | 2,203.2M | $1,140.15 | $5,948.70 | $3,625.78 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 11,554 | 27.3M | 2.7M | 915.1M | $431.96 | $2,471.01 | $1,591.62 |
| claude-sonnet-4-5 | 11,497 | 32K | 2.8M | 453.5M | $256.57 | $1,224.56 | $713.32 |
| gpt-5.5 | 10,538 | 31.2M | 1.8M | 475.8M | $233.74 | $1,284.91 | $1,056.52 |
| claude-sonnet-4-5 | 4,501 | 50K | 1.9M | 311.9M | $226.43 | $842.23 | $494.67 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 468 | 527 | 201K | 43.9M | $104.76 | $593.93 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 712 | 4.5M | 65K | 19.9M | $2.06 | $37.36 | $77.97 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **119,659** | **75.7M** | **35.8M** | **6,775.6M** | **$3,832.67** | **$19,099.35** | **$11,037.20** |

_7,095.0M total tokens processed. 95.5% cache hit rate._

_$30,136.55 total saved ($19,099.35 caching + $11,037.20 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-03 13:16 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
