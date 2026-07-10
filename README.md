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
| Screen time (Linux) | 24h | 3.7h | 63.4h | ~1,351h* |
| User AI session hours | 7.0h | 33.0h | 104.2h | 156.9h |
| AI worker hours | 49.9h | 193.0h | 528.5h | 629.5h |
| AI concurrency hours | 60.3h | 255.7h | 709.0h | 901.3h |
| Interactive sessions | 4 | 57 | 240 | 347 |
| Worker sessions | 48 | 192 | 539 | 878 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 42 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 50,872 | 53K | 18.9M | 2,631.8M | $1,365.47 | $7,106.12 | $4,294.60 |
| deepseek-v4-flash-free | 14,016 | 35.6M | 3.2M | 1,127.5M | $533.23 | $3,044.33 | $1,975.51 |
| claude-opus-4-6 | 2,275 | 2K | 915K | 158.7M | $411.66 | $2,142.98 | $0.00 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 5,573 | 63K | 2.4M | 385.1M | $288.85 | $1,039.99 | $607.05 |
| gpt-5.5 | 10,643 | 30.3M | 1.8M | 453.2M | $225.73 | $1,223.66 | $1,018.14 |
| gpt-5.4 | 5,972 | 21.6M | 1.2M | 274.5M | $152.45 | $514.72 | $594.46 |
| claude-haiku-4-5 | 23,950 | 38K | 5.2M | 1,247.9M | $152.25 | $898.55 | $2,144.45 |
| claude-sonnet-4-0 | 1,549 | 15K | 421K | 97.7M | $61.84 | $263.88 | $142.76 |
| claude-opus-4-0 | 119 | 1K | 41K | 8.2M | $27.31 | $111.72 | $0.00 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.5-fast | 183 | 1.0M | 44K | 22.3M | $9.17 | $60.30 | $42.64 |
| gpt-5.4-mini | 1,240 | 5.7M | 148K | 47.1M | $3.52 | $88.37 | $123.18 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **130,956** | **95.1M** | **38.1M** | **7,035.2M** | **$3,584.19** | **$18,156.28** | **$11,847.95** |

_7,352.9M total tokens processed. 95.7% cache hit rate._

_$30,004.23 total saved ($18,156.28 caching + $11,847.95 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 67,139 | 71K | 25.9M | 3,434.6M | $1,809.89 | $9,273.68 | $5,678.65 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 16,193 | 41.0M | 3.8M | 1,303.2M | $617.63 | $3,518.79 | $2,284.65 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-opus-4-6 | 2,275 | 2K | 915K | 158.7M | $411.66 | $2,142.98 | $0.00 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,694 | 64K | 2.4M | 394.3M | $295.26 | $1,064.82 | $621.12 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,169 | 22.2M | 1.3M | 285.5M | $157.50 | $535.48 | $613.48 |
| claude-haiku-4-5 | 23,986 | 38K | 5.2M | 1,249.0M | $152.46 | $899.30 | $2,146.37 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,240 | 5.7M | 148K | 47.1M | $3.52 | $88.37 | $123.18 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **165,997** | **108.0M** | **50.4M** | **9,157.3M** | **$5,314.48** | **$26,425.17** | **$14,949.55** |

_9,589.5M total tokens processed. 95.5% cache hit rate._

_$41,374.72 total saved ($26,425.17 caching + $14,949.55 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-10 18:06 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
