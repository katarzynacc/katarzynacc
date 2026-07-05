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
| Screen time (Linux) | 24h | 4.7h | 84.2h | ~1,351h* |
| User AI session hours | 7.2h | 42.4h | 109.3h | 137.3h |
| AI worker hours | 23.6h | 155.0h | 405.2h | 475.2h |
| AI concurrency hours | 33.5h | 230.6h | 592.3h | 714.7h |
| Interactive sessions | 13 | 107 | 252 | 309 |
| Worker sessions | 28 | 160 | 499 | 736 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 38 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 31,817 | 33K | 11.9M | 1,760.8M | $882.40 | $4,754.17 | $2,828.75 |
| deepseek-v4-flash-free | 13,446 | 33.0M | 3.1M | 1,068.6M | $507.15 | $2,885.43 | $1,870.93 |
| claude-sonnet-4-5 | 16,266 | 43K | 4.0M | 651.7M | $362.51 | $1,759.70 | $1,024.27 |
| claude-opus-4-0 | 1,486 | 14K | 390K | 110.1M | $325.74 | $1,486.60 | $0.00 |
| claude-sonnet-4-5 | 5,002 | 56K | 2.2M | 344.8M | $261.56 | $931.21 | $548.86 |
| gpt-5.5 | 11,853 | 34.5M | 2.0M | 519.5M | $256.72 | $1,402.68 | $1,159.51 |
| claude-haiku-4-5 | 23,029 | 36K | 5.0M | 1,191.9M | $146.01 | $858.18 | $2,052.30 |
| claude-sonnet-4-0 | 3,302 | 33K | 955K | 205.1M | $133.10 | $553.92 | $303.90 |
| claude-opus-4-6 | 474 | 537 | 204K | 44.0M | $106.07 | $595.22 | $0.00 |
| gpt-5.4 | 2,944 | 10.4M | 585K | 137.1M | $74.16 | $257.23 | $288.13 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 991 | 5.0M | 113K | 36.6M | $2.87 | $68.78 | $102.59 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **111,314** | **86.1M** | **30.9M** | **6,132.2M** | **$3,115.40** | **$15,812.96** | **$10,283.83** |

_6,412.3M total tokens processed. 95.6% cache hit rate._

_$26,096.79 total saved ($15,812.96 caching + $10,283.83 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 44,174 | 46K | 17.4M | 2,359.7M | $1,222.80 | $6,371.23 | $3,879.27 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 13,446 | 33.0M | 3.1M | 1,068.6M | $507.15 | $2,885.43 | $1,870.93 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,266 | 43K | 4.0M | 651.7M | $362.51 | $1,759.70 | $1,024.27 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-sonnet-4-5 | 5,002 | 56K | 2.2M | 344.8M | $261.56 | $931.21 | $548.86 |
| claude-haiku-4-5 | 23,061 | 36K | 5.0M | 1,192.9M | $146.16 | $858.92 | $2,054.19 |
| claude-opus-4-6 | 474 | 537 | 204K | 44.0M | $106.07 | $595.22 | $0.00 |
| gpt-5.4 | 2,944 | 10.4M | 585K | 137.1M | $74.16 | $257.23 | $288.13 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 991 | 5.0M | 113K | 36.6M | $2.87 | $68.78 | $102.59 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **133,036** | **87.5M** | **39.3M** | **7,452.2M** | **$4,179.37** | **$20,825.21** | **$12,201.44** |

_7,806.2M total tokens processed. 95.5% cache hit rate._

_$33,026.66 total saved ($20,825.21 caching + $12,201.44 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-05 20:54 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
