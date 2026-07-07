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
| Screen time (Linux) | 24h | 4.7h | 63.4h | ~1,351h* |
| User AI session hours | 5.9h | 41.9h | 109.7h | 145.8h |
| AI worker hours | 53.4h | 199.5h | 460.9h | 546.2h |
| AI concurrency hours | 64.9h | 276.7h | 648.9h | 801.6h |
| Interactive sessions | 18 | 98 | 251 | 334 |
| Worker sessions | 49 | 192 | 511 | 810 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 39 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 40,767 | 43K | 15.2M | 2,147.9M | $1,102.27 | $5,799.35 | $3,491.57 |
| deepseek-v4-flash-free | 14,710 | 36.5M | 3.4M | 1,176.2M | $557.92 | $3,175.75 | $2,058.41 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-6 | 1,573 | 1K | 644K | 115.9M | $292.89 | $1,565.92 | $0.00 |
| claude-sonnet-4-5 | 5,532 | 62K | 2.3M | 379.3M | $285.14 | $1,024.18 | $599.24 |
| gpt-5.5 | 10,686 | 30.4M | 1.8M | 455.6M | $226.69 | $1,230.16 | $1,022.52 |
| claude-opus-4-0 | 947 | 9K | 246K | 64.8M | $194.04 | $875.19 | $0.00 |
| claude-haiku-4-5 | 23,559 | 37K | 5.1M | 1,218.3M | $149.18 | $877.19 | $2,096.88 |
| claude-sonnet-4-0 | 2,936 | 29K | 850K | 184.8M | $118.63 | $499.13 | $273.25 |
| gpt-5.4 | 4,224 | 15.4M | 884K | 193.9M | $107.76 | $363.74 | $420.30 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 394 | 1.6M | 88K | 41.9M | $16.29 | $113.17 | $75.26 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **123,169** | **89.7M** | **35.1M** | **6,693.4M** | **$3,459.73** | **$17,515.74** | **$11,195.57** |

_6,997.7M total tokens processed. 95.7% cache hit rate._

_$28,711.31 total saved ($17,515.74 caching + $11,195.57 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 54,272 | 57K | 21.1M | 2,815.5M | $1,475.13 | $7,601.90 | $4,648.88 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 14,710 | 36.5M | 3.4M | 1,176.2M | $557.92 | $3,175.75 | $2,058.41 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-6 | 1,573 | 1K | 644K | 115.9M | $292.89 | $1,565.92 | $0.00 |
| claude-sonnet-4-5 | 5,653 | 64K | 2.4M | 388.5M | $291.56 | $1,049.01 | $613.30 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-haiku-4-5 | 23,591 | 37K | 5.1M | 1,219.3M | $149.34 | $877.93 | $2,098.77 |
| gpt-5.4 | 4,420 | 15.9M | 920K | 205.0M | $112.76 | $384.49 | $439.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **148,542** | **96.6M** | **44.5M** | **8,242.8M** | **$4,749.09** | **$23,627.24** | **$13,445.02** |

_8,634.2M total tokens processed. 95.5% cache hit rate._

_$37,072.26 total saved ($23,627.24 caching + $13,445.02 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-07 08:22 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
