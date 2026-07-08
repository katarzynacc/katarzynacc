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
| Screen time (Linux) | 13h | 17.7h | 76.4h | ~1,351h* |
| User AI session hours | 4.2h | 41.7h | 110.2h | 149.9h |
| AI worker hours | 44.6h | 217.3h | 489.1h | 577.1h |
| AI concurrency hours | 51.7h | 293.1h | 677.7h | 838.6h |
| Interactive sessions | 11 | 89 | 255 | 343 |
| Worker sessions | 56 | 209 | 525 | 837 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 40 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 45,770 | 48K | 17.3M | 2,406.5M | $1,242.67 | $6,497.76 | $3,927.83 |
| deepseek-v4-flash-free | 14,708 | 36.9M | 3.4M | 1,175.7M | $559.32 | $3,174.52 | $2,063.86 |
| claude-sonnet-4-5 | 16,155 | 43K | 4.0M | 650.6M | $360.69 | $1,756.86 | $1,021.54 |
| claude-opus-4-6 | 1,896 | 2K | 769K | 137.2M | $348.87 | $1,853.21 | $0.00 |
| claude-sonnet-4-5 | 5,573 | 63K | 2.4M | 385.1M | $288.85 | $1,039.99 | $607.05 |
| gpt-5.5 | 10,643 | 30.3M | 1.8M | 453.2M | $225.73 | $1,223.66 | $1,018.14 |
| claude-opus-4-0 | 947 | 9K | 246K | 64.8M | $194.04 | $875.19 | $0.00 |
| claude-haiku-4-5 | 23,871 | 37K | 5.2M | 1,241.5M | $151.59 | $893.89 | $2,133.66 |
| gpt-5.4 | 4,223 | 15.4M | 884K | 193.9M | $107.72 | $363.74 | $420.11 |
| claude-sonnet-4-0 | 2,285 | 22K | 647K | 144.3M | $92.37 | $389.74 | $212.36 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.5-fast | 184 | 1.0M | 44K | 22.3M | $9.17 | $60.30 | $42.64 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **127,473** | **89.6M** | **37.0M** | **6,921.9M** | **$3,619.47** | **$18,316.57** | **$11,556.44** |

_7,234.0M total tokens processed. 95.7% cache hit rate._

_$29,873.01 total saved ($18,316.57 caching + $11,556.44 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 59,275 | 62K | 23.2M | 3,074.1M | $1,615.53 | $8,300.31 | $5,085.14 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 15,236 | 38.1M | 3.6M | 1,217.4M | $578.57 | $3,287.14 | $2,135.37 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-6 | 1,896 | 2K | 769K | 137.2M | $348.87 | $1,853.21 | $0.00 |
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
| **Total** | **154,747** | **98.2M** | **46.9M** | **8,593.0M** | **$4,972.23** | **$24,756.85** | **$14,002.83** |

_8,998.5M total tokens processed. 95.5% cache hit rate._

_$38,759.68 total saved ($24,756.85 caching + $14,002.83 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-08 00:01 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
