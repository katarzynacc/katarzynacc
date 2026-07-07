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
| User AI session hours | 6.6h | 41.8h | 109.7h | 145.7h |
| AI worker hours | 55.9h | 199.0h | 460.4h | 545.6h |
| AI concurrency hours | 67.4h | 275.1h | 647.6h | 799.9h |
| Interactive sessions | 17 | 97 | 251 | 333 |
| Worker sessions | 51 | 191 | 511 | 809 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 39 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 40,563 | 42K | 15.1M | 2,140.3M | $1,097.81 | $5,778.98 | $3,478.72 |
| deepseek-v4-flash-free | 14,710 | 36.5M | 3.4M | 1,176.2M | $557.92 | $3,175.75 | $2,058.41 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-6 | 1,573 | 1K | 644K | 115.9M | $292.89 | $1,565.92 | $0.00 |
| claude-sonnet-4-5 | 5,502 | 62K | 2.3M | 377.1M | $282.11 | $1,018.22 | $595.98 |
| gpt-5.5 | 10,686 | 30.4M | 1.8M | 455.6M | $226.69 | $1,230.16 | $1,022.52 |
| claude-opus-4-0 | 947 | 9K | 246K | 64.8M | $194.04 | $875.19 | $0.00 |
| claude-haiku-4-5 | 23,559 | 37K | 5.1M | 1,218.3M | $149.18 | $877.19 | $2,096.88 |
| claude-sonnet-4-0 | 2,936 | 29K | 850K | 184.8M | $118.63 | $499.13 | $273.25 |
| gpt-5.4 | 4,224 | 15.4M | 884K | 193.9M | $107.76 | $363.74 | $420.30 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 429 | 1.8M | 96K | 43.5M | $17.44 | $117.66 | $80.43 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **122,970** | **90.0M** | **35.0M** | **6,685.4M** | **$3,453.39** | **$17,493.90** | **$11,184.63** |

_6,988.9M total tokens processed. 95.7% cache hit rate._

_$28,678.53 total saved ($17,493.90 caching + $11,184.63 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 54,069 | 57K | 21.0M | 2,808.0M | $1,470.69 | $7,581.67 | $4,636.11 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 14,710 | 36.5M | 3.4M | 1,176.2M | $557.92 | $3,175.75 | $2,058.41 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-6 | 1,573 | 1K | 644K | 115.9M | $292.89 | $1,565.92 | $0.00 |
| claude-sonnet-4-5 | 5,623 | 63K | 2.4M | 386.3M | $288.52 | $1,043.05 | $610.05 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-haiku-4-5 | 23,591 | 37K | 5.1M | 1,219.3M | $149.34 | $877.93 | $2,098.77 |
| gpt-5.4 | 4,420 | 15.9M | 920K | 205.0M | $112.76 | $384.49 | $439.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **148,309** | **96.6M** | **44.4M** | **8,233.1M** | **$4,741.61** | **$23,601.05** | **$13,428.99** |

_8,623.5M total tokens processed. 95.5% cache hit rate._

_$37,030.04 total saved ($23,601.05 caching + $13,428.99 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-07 07:22 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
