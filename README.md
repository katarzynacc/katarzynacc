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
| User AI session hours | 3.5h | 38.4h | 105.1h | 132.0h |
| AI worker hours | 21.5h | 150.6h | 399.6h | 469.3h |
| AI concurrency hours | 26.8h | 221.9h | 581.3h | 701.9h |
| Interactive sessions | 9 | 106 | 246 | 302 |
| Worker sessions | 24 | 159 | 496 | 731 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 37 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 31,808 | 33K | 11.9M | 1,759.6M | $882.05 | $4,751.12 | $2,826.61 |
| deepseek-v4-flash-free | 12,864 | 30.6M | 3.0M | 1,025.0M | $483.19 | $2,767.51 | $1,781.97 |
| claude-opus-4-0 | 1,924 | 18K | 518K | 138.4M | $415.41 | $1,869.17 | $0.00 |
| claude-sonnet-4-5 | 15,940 | 42K | 3.9M | 639.1M | $355.59 | $1,725.75 | $1,004.56 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
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
| **Total** | **110,311** | **83.9M** | **30.6M** | **6,072.1M** | **$3,174.12** | **$16,046.02** | **$10,126.15** |

_6,350.9M total tokens processed. 95.6% cache hit rate._

_$26,172.17 total saved ($16,046.02 caching + $10,126.15 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 44,131 | 46K | 17.4M | 2,357.6M | $1,221.50 | $6,365.54 | $3,875.29 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 12,864 | 30.6M | 3.0M | 1,025.0M | $483.19 | $2,767.51 | $1,781.97 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 15,940 | 42K | 3.9M | 639.1M | $355.59 | $1,725.75 | $1,004.56 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
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
| **Total** | **131,038** | **83.9M** | **38.8M** | **7,331.0M** | **$4,130.61** | **$20,589.39** | **$11,980.92** |

_7,679.1M total tokens processed. 95.5% cache hit rate._

_$32,570.32 total saved ($20,589.39 caching + $11,980.92 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-05 13:53 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
