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
| Screen time (Linux) | 24h | 52.3h | 84.2h | ~1,351h* |
| User AI session hours | 3.6h | 38.1h | 105.3h | 132.7h |
| AI worker hours | 22.6h | 152.7h | 402.1h | 471.9h |
| AI concurrency hours | 28.3h | 223.2h | 584.0h | 705.4h |
| Interactive sessions | 10 | 104 | 248 | 304 |
| Worker sessions | 24 | 157 | 497 | 732 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 37 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 31,816 | 33K | 11.9M | 1,760.8M | $882.35 | $4,754.17 | $2,828.75 |
| deepseek-v4-flash-free | 12,978 | 31.0M | 3.0M | 1,034.4M | $488.17 | $2,792.99 | $1,799.29 |
| claude-sonnet-4-5 | 16,000 | 43K | 3.9M | 640.9M | $356.59 | $1,730.56 | $1,007.44 |
| claude-opus-4-0 | 1,596 | 15K | 412K | 115.1M | $339.25 | $1,554.41 | $0.00 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-sonnet-4-5 | 4,948 | 56K | 2.2M | 343.1M | $259.42 | $926.39 | $545.26 |
| claude-haiku-4-5 | 22,974 | 36K | 5.0M | 1,188.3M | $145.66 | $855.59 | $2,046.47 |
| claude-sonnet-4-0 | 3,476 | 34K | 998K | 217.7M | $140.62 | $587.95 | $321.64 |
| claude-opus-4-6 | 473 | 534 | 203K | 44.0M | $105.55 | $595.22 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 929 | 4.9M | 101K | 32.9M | $2.69 | $61.87 | $97.16 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **110,798** | **84.3M** | **30.7M** | **6,092.5M** | **$3,107.99** | **$15,787.68** | **$10,203.32** |

_6,370.8M total tokens processed. 95.6% cache hit rate._

_$25,991.00 total saved ($15,787.68 caching + $10,203.32 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 44,173 | 46K | 17.4M | 2,359.7M | $1,222.75 | $6,371.23 | $3,879.26 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 12,978 | 31.0M | 3.0M | 1,034.4M | $488.17 | $2,792.99 | $1,799.29 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,000 | 43K | 3.9M | 640.9M | $356.59 | $1,730.56 | $1,007.44 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-sonnet-4-5 | 4,948 | 56K | 2.2M | 343.1M | $259.42 | $926.39 | $545.26 |
| claude-haiku-4-5 | 23,006 | 36K | 5.0M | 1,189.3M | $145.82 | $856.34 | $2,048.36 |
| claude-opus-4-6 | 473 | 534 | 203K | 44.0M | $105.55 | $595.22 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 929 | 4.9M | 101K | 32.9M | $2.69 | $61.87 | $97.16 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **131,923** | **84.4M** | **39.0M** | **7,376.8M** | **$4,141.86** | **$20,649.37** | **$12,061.92** |

_7,726.5M total tokens processed. 95.5% cache hit rate._

_$32,711.29 total saved ($20,649.37 caching + $12,061.92 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-05 16:53 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
