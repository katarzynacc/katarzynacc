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
| User AI session hours | 2.9h | 37.6h | 104.5h | 132.0h |
| AI worker hours | 20.2h | 150.3h | 399.6h | 469.4h |
| AI concurrency hours | 24.9h | 220.2h | 580.6h | 702.1h |
| Interactive sessions | 9 | 104 | 247 | 303 |
| Worker sessions | 23 | 156 | 496 | 731 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 37 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 31,815 | 33K | 11.9M | 1,759.8M | $882.15 | $4,751.69 | $2,826.99 |
| deepseek-v4-flash-free | 12,877 | 30.7M | 3.0M | 1,025.2M | $483.60 | $2,768.14 | $1,783.40 |
| claude-opus-4-0 | 1,712 | 16K | 446K | 121.7M | $363.51 | $1,643.35 | $0.00 |
| claude-sonnet-4-5 | 15,951 | 42K | 3.9M | 639.4M | $355.86 | $1,726.57 | $1,005.13 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-sonnet-4-5 | 4,947 | 56K | 2.2M | 343.1M | $259.34 | $926.39 | $545.23 |
| claude-haiku-4-5 | 22,342 | 36K | 4.9M | 1,156.8M | $141.88 | $832.93 | $1,992.15 |
| claude-sonnet-4-0 | 3,476 | 34K | 998K | 217.7M | $140.62 | $587.95 | $321.64 |
| claude-opus-4-6 | 473 | 534 | 203K | 44.0M | $105.55 | $595.22 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 914 | 4.8M | 97K | 32.5M | $2.64 | $60.94 | $95.75 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **110,115** | **83.9M** | **30.6M** | **6,055.5M** | **$3,122.84** | **$15,821.71** | **$10,127.62** |

_6,333.3M total tokens processed. 95.6% cache hit rate._

_$25,949.34 total saved ($15,821.71 caching + $10,127.62 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 44,140 | 46K | 17.4M | 2,357.8M | $1,221.74 | $6,366.11 | $3,875.71 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 12,877 | 30.7M | 3.0M | 1,025.2M | $483.60 | $2,768.14 | $1,783.40 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 15,951 | 42K | 3.9M | 639.4M | $355.86 | $1,726.57 | $1,005.13 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-sonnet-4-5 | 4,947 | 56K | 2.2M | 343.1M | $259.34 | $926.39 | $545.23 |
| claude-haiku-4-5 | 22,374 | 36K | 4.9M | 1,157.8M | $142.03 | $833.67 | $1,994.04 |
| claude-opus-4-6 | 473 | 534 | 203K | 44.0M | $105.55 | $595.22 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 914 | 4.8M | 97K | 32.5M | $2.64 | $60.94 | $95.75 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **131,092** | **84.0M** | **38.8M** | **7,332.3M** | **$4,131.63** | **$20,591.81** | **$11,984.42** |

_7,680.6M total tokens processed. 95.5% cache hit rate._

_$32,576.23 total saved ($20,591.81 caching + $11,984.42 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-05 15:53 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
