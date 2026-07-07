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
| Screen time (Linux) | 23h | 4.7h | 63.4h | ~1,351h* |
| User AI session hours | 7.1h | 41.8h | 110.1h | 145.7h |
| AI worker hours | 53.1h | 188.0h | 451.9h | 533.1h |
| AI concurrency hours | 65.3h | 264.1h | 640.2h | 787.4h |
| Interactive sessions | 17 | 97 | 254 | 333 |
| Worker sessions | 55 | 178 | 510 | 795 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 39 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 38,562 | 40K | 14.5M | 2,060.8M | $1,052.36 | $5,564.37 | $3,343.75 |
| deepseek-v4-flash-free | 14,710 | 36.5M | 3.4M | 1,176.2M | $557.92 | $3,175.75 | $2,058.41 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-6 | 1,531 | 1K | 637K | 114.4M | $289.11 | $1,544.83 | $0.00 |
| claude-sonnet-4-5 | 5,502 | 62K | 2.3M | 377.1M | $282.11 | $1,018.22 | $595.98 |
| gpt-5.5 | 10,686 | 30.4M | 1.8M | 455.6M | $226.69 | $1,230.16 | $1,022.52 |
| claude-opus-4-0 | 947 | 9K | 246K | 64.8M | $194.04 | $875.19 | $0.00 |
| claude-haiku-4-5 | 23,417 | 37K | 5.1M | 1,210.0M | $148.26 | $871.24 | $2,083.43 |
| claude-sonnet-4-0 | 2,936 | 29K | 850K | 184.8M | $118.63 | $499.13 | $273.25 |
| gpt-5.4 | 4,224 | 15.4M | 884K | 193.9M | $107.76 | $363.74 | $420.30 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 429 | 1.8M | 96K | 43.5M | $17.44 | $117.66 | $80.43 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **120,785** | **90.0M** | **34.3M** | **6,596.0M** | **$3,403.24** | **$17,252.25** | **$11,036.21** |

_6,895.7M total tokens processed. 95.7% cache hit rate._

_$28,288.46 total saved ($17,252.25 caching + $11,036.21 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 52,070 | 55K | 20.4M | 2,728.5M | $1,425.27 | $7,367.14 | $4,501.18 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 14,710 | 36.5M | 3.4M | 1,176.2M | $557.92 | $3,175.75 | $2,058.41 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-6 | 1,531 | 1K | 637K | 114.4M | $289.11 | $1,544.83 | $0.00 |
| claude-sonnet-4-5 | 5,623 | 63K | 2.4M | 386.3M | $288.52 | $1,043.05 | $610.05 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-haiku-4-5 | 23,449 | 37K | 5.1M | 1,211.0M | $148.41 | $871.98 | $2,085.32 |
| gpt-5.4 | 4,420 | 15.9M | 920K | 205.0M | $112.76 | $384.49 | $439.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **146,126** | **96.6M** | **43.7M** | **8,143.8M** | **$4,691.48** | **$23,359.48** | **$13,280.62** |

_8,530.4M total tokens processed. 95.5% cache hit rate._

_$36,640.10 total saved ($23,359.48 caching + $13,280.62 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-07 00:10 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
