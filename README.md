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
| User AI session hours | 5.8h | 32.6h | 103.8h | 155.8h |
| AI worker hours | 46.8h | 189.9h | 525.4h | 626.4h |
| AI concurrency hours | 55.1h | 251.7h | 705.0h | 896.2h |
| Interactive sessions | 4 | 58 | 242 | 347 |
| Worker sessions | 44 | 188 | 535 | 874 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 42 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 50,592 | 53K | 18.8M | 2,618.4M | $1,358.46 | $7,069.75 | $4,273.36 |
| deepseek-v4-flash-free | 13,876 | 35.4M | 3.2M | 1,110.9M | $526.75 | $2,999.48 | $1,950.91 |
| claude-opus-4-6 | 2,254 | 2K | 907K | 158.3M | $408.58 | $2,137.06 | $0.00 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 5,573 | 63K | 2.4M | 385.1M | $288.85 | $1,039.99 | $607.05 |
| gpt-5.5 | 10,643 | 30.3M | 1.8M | 453.2M | $225.73 | $1,223.66 | $1,018.14 |
| claude-haiku-4-5 | 23,950 | 38K | 5.2M | 1,247.9M | $152.25 | $898.55 | $2,144.45 |
| gpt-5.4 | 5,678 | 20.3M | 1.2M | 261.6M | $144.33 | $490.68 | $562.31 |
| claude-sonnet-4-0 | 1,549 | 15K | 421K | 97.7M | $61.84 | $263.88 | $142.76 |
| claude-opus-4-0 | 119 | 1K | 41K | 8.2M | $27.31 | $111.72 | $0.00 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.5-fast | 183 | 1.0M | 44K | 22.3M | $9.17 | $60.30 | $42.64 |
| gpt-5.4-mini | 1,211 | 5.6M | 143K | 46.2M | $3.45 | $86.69 | $120.88 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **130,192** | **93.5M** | **37.9M** | **6,990.9M** | **$3,559.43** | **$18,043.40** | **$11,767.67** |

_7,306.4M total tokens processed. 95.7% cache hit rate._

_$29,811.07 total saved ($18,043.40 caching + $11,767.67 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 66,859 | 70K | 25.8M | 3,421.2M | $1,802.87 | $9,237.31 | $5,657.40 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 15,976 | 40.6M | 3.7M | 1,281.9M | $608.85 | $3,461.32 | $2,251.65 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-opus-4-6 | 2,254 | 2K | 907K | 158.3M | $408.58 | $2,137.06 | $0.00 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,694 | 64K | 2.4M | 394.3M | $295.26 | $1,064.82 | $621.12 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-haiku-4-5 | 23,986 | 38K | 5.2M | 1,249.0M | $152.46 | $899.30 | $2,146.37 |
| gpt-5.4 | 5,875 | 20.9M | 1.2M | 272.7M | $149.37 | $511.43 | $581.34 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,211 | 5.6M | 143K | 46.2M | $3.45 | $86.69 | $120.88 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **165,156** | **106.2M** | **50.1M** | **9,108.4M** | **$5,287.40** | **$26,299.67** | **$14,860.87** |

_9,538.1M total tokens processed. 95.5% cache hit rate._

_$41,160.54 total saved ($26,299.67 caching + $14,860.87 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-10 17:06 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
