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
| User AI session hours | 4.5h | 39.0h | 106.2h | 133.6h |
| AI worker hours | 25.1h | 155.3h | 404.7h | 474.5h |
| AI concurrency hours | 32.5h | 227.5h | 588.3h | 709.7h |
| Interactive sessions | 13 | 107 | 251 | 307 |
| Worker sessions | 28 | 161 | 501 | 736 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 37 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 31,816 | 33K | 11.9M | 1,760.8M | $882.35 | $4,754.17 | $2,828.75 |
| deepseek-v4-flash-free | 13,154 | 32.0M | 3.1M | 1,046.0M | $495.38 | $2,824.28 | $1,826.73 |
| claude-sonnet-4-5 | 16,196 | 43K | 4.0M | 649.4M | $361.03 | $1,753.41 | $1,020.63 |
| claude-opus-4-0 | 1,596 | 15K | 412K | 115.1M | $339.25 | $1,554.41 | $0.00 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-sonnet-4-5 | 5,002 | 56K | 2.2M | 344.8M | $261.56 | $931.21 | $548.86 |
| claude-haiku-4-5 | 23,029 | 36K | 5.0M | 1,191.9M | $146.01 | $858.18 | $2,052.30 |
| claude-sonnet-4-0 | 3,476 | 34K | 998K | 217.7M | $140.62 | $587.95 | $321.64 |
| claude-opus-4-6 | 474 | 537 | 204K | 44.0M | $106.07 | $595.22 | $0.00 |
| gpt-5.4 | 2,943 | 10.4M | 585K | 137.1M | $74.16 | $257.23 | $288.13 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 991 | 5.0M | 113K | 36.6M | $2.87 | $68.78 | $102.59 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **111,547** | **86.3M** | **30.9M** | **6,142.9M** | **$3,132.21** | **$15,896.09** | **$10,295.00** |

_6,424.1M total tokens processed. 95.6% cache hit rate._

_$26,191.09 total saved ($15,896.09 caching + $10,295.00 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 44,173 | 46K | 17.4M | 2,359.7M | $1,222.75 | $6,371.23 | $3,879.26 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 13,154 | 32.0M | 3.1M | 1,046.0M | $495.38 | $2,824.28 | $1,826.73 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,196 | 43K | 4.0M | 649.4M | $361.03 | $1,753.41 | $1,020.63 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-sonnet-4-5 | 5,002 | 56K | 2.2M | 344.8M | $261.56 | $931.21 | $548.86 |
| claude-haiku-4-5 | 23,061 | 36K | 5.0M | 1,192.9M | $146.16 | $858.92 | $2,054.19 |
| claude-opus-4-6 | 474 | 537 | 204K | 44.0M | $106.07 | $595.22 | $0.00 |
| gpt-5.4 | 2,943 | 10.4M | 585K | 137.1M | $74.16 | $257.23 | $288.13 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 991 | 5.0M | 113K | 36.6M | $2.87 | $68.78 | $102.59 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **132,672** | **86.4M** | **39.2M** | **7,427.2M** | **$4,166.07** | **$20,757.77** | **$12,153.60** |

_7,779.9M total tokens processed. 95.5% cache hit rate._

_$32,911.37 total saved ($20,757.77 caching + $12,153.60 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-05 18:01 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
