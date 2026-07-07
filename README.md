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
| User AI session hours | 7.1h | 41.8h | 110.1h | 145.7h |
| AI worker hours | 56.6h | 191.5h | 454.6h | 536.6h |
| AI concurrency hours | 68.8h | 267.6h | 642.9h | 791.0h |
| Interactive sessions | 17 | 97 | 254 | 333 |
| Worker sessions | 61 | 184 | 516 | 801 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 39 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 39,246 | 41K | 14.7M | 2,088.4M | $1,067.71 | $5,638.86 | $3,389.53 |
| deepseek-v4-flash-free | 14,710 | 36.5M | 3.4M | 1,176.2M | $557.92 | $3,175.75 | $2,058.41 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-6 | 1,559 | 1K | 643K | 115.3M | $291.75 | $1,557.44 | $0.00 |
| claude-sonnet-4-5 | 5,502 | 62K | 2.3M | 377.1M | $282.11 | $1,018.22 | $595.98 |
| gpt-5.5 | 10,686 | 30.4M | 1.8M | 455.6M | $226.69 | $1,230.16 | $1,022.52 |
| claude-opus-4-0 | 947 | 9K | 246K | 64.8M | $194.04 | $875.19 | $0.00 |
| claude-haiku-4-5 | 23,508 | 37K | 5.1M | 1,214.4M | $148.81 | $874.38 | $2,090.81 |
| claude-sonnet-4-0 | 2,936 | 29K | 850K | 184.8M | $118.63 | $499.13 | $273.25 |
| gpt-5.4 | 4,224 | 15.4M | 884K | 193.9M | $107.76 | $363.74 | $420.30 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 429 | 1.8M | 96K | 43.5M | $17.44 | $117.66 | $80.43 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **121,588** | **90.0M** | **34.6M** | **6,628.9M** | **$3,421.78** | **$17,342.50** | **$11,089.37** |

_6,929.9M total tokens processed. 95.7% cache hit rate._

_$28,431.87 total saved ($17,342.50 caching + $11,089.37 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 52,751 | 55K | 20.6M | 2,756.0M | $1,440.58 | $7,441.42 | $4,546.84 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 14,710 | 36.5M | 3.4M | 1,176.2M | $557.92 | $3,175.75 | $2,058.41 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-6 | 1,560 | 1K | 643K | 115.4M | $291.83 | $1,558.01 | $0.00 |
| claude-sonnet-4-5 | 5,623 | 63K | 2.4M | 386.3M | $288.52 | $1,043.05 | $610.05 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-haiku-4-5 | 23,540 | 37K | 5.1M | 1,215.4M | $148.97 | $875.12 | $2,092.70 |
| gpt-5.4 | 4,420 | 15.9M | 920K | 205.0M | $112.76 | $384.49 | $439.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **146,927** | **96.6M** | **43.9M** | **8,176.6M** | **$4,710.07** | **$23,450.08** | **$13,333.65** |

_8,564.6M total tokens processed. 95.5% cache hit rate._

_$36,783.73 total saved ($23,450.08 caching + $13,333.65 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-07 01:09 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
