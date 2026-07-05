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
| User AI session hours | 4.2h | 39.2h | 105.8h | 132.0h |
| AI worker hours | 21.8h | 154.2h | 399.3h | 469.0h |
| AI concurrency hours | 28.2h | 227.2h | 582.4h | 701.6h |
| Interactive sessions | 9 | 106 | 247 | 302 |
| Worker sessions | 25 | 160 | 495 | 730 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 37 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 31,809 | 33K | 11.9M | 1,759.6M | $882.13 | $4,751.12 | $2,826.63 |
| deepseek-v4-flash-free | 12,863 | 30.6M | 3.0M | 1,024.9M | $483.16 | $2,767.33 | $1,781.86 |
| claude-opus-4-0 | 1,959 | 18K | 529K | 143.4M | $426.80 | $1,936.99 | $0.00 |
| claude-sonnet-4-5 | 15,940 | 42K | 3.9M | 639.1M | $355.59 | $1,725.75 | $1,004.56 |
| gpt-5.5 | 12,098 | 35.5M | 2.0M | 535.0M | $264.35 | $1,444.69 | $1,194.21 |
| claude-sonnet-4-5 | 4,947 | 56K | 2.2M | 343.1M | $259.34 | $926.39 | $545.23 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-sonnet-4-0 | 3,480 | 34K | 999K | 217.8M | $140.73 | $588.11 | $321.75 |
| claude-opus-4-6 | 473 | 534 | 203K | 44.0M | $105.55 | $595.22 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 914 | 4.8M | 97K | 32.5M | $2.64 | $60.94 | $95.75 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **110,278** | **83.6M** | **30.6M** | **6,074.5M** | **$3,184.11** | **$16,106.95** | **$10,119.48** |

_6,353.1M total tokens processed. 95.6% cache hit rate._

_$26,226.43 total saved ($16,106.95 caching + $10,119.48 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 44,131 | 46K | 17.4M | 2,357.6M | $1,221.50 | $6,365.54 | $3,875.29 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 12,863 | 30.6M | 3.0M | 1,024.9M | $483.16 | $2,767.33 | $1,781.86 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 15,940 | 42K | 3.9M | 639.1M | $355.59 | $1,725.75 | $1,004.56 |
| gpt-5.5 | 12,098 | 35.5M | 2.0M | 535.0M | $264.35 | $1,444.69 | $1,194.21 |
| claude-sonnet-4-5 | 4,947 | 56K | 2.2M | 343.1M | $259.34 | $926.39 | $545.23 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 473 | 534 | 203K | 44.0M | $105.55 | $595.22 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 914 | 4.8M | 97K | 32.5M | $2.64 | $60.94 | $95.75 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **130,969** | **83.7M** | **38.8M** | **7,328.4M** | **$4,129.13** | **$20,582.50** | **$11,974.23** |

_7,676.3M total tokens processed. 95.5% cache hit rate._

_$32,556.74 total saved ($20,582.50 caching + $11,974.23 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-05 12:01 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
