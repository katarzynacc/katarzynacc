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
| User AI session hours | 6.8h | 41.7h | 109.0h | 136.5h |
| AI worker hours | 25.6h | 155.9h | 405.1h | 475.1h |
| AI concurrency hours | 35.3h | 231.3h | 592.1h | 713.7h |
| Interactive sessions | 15 | 108 | 253 | 309 |
| Worker sessions | 28 | 161 | 500 | 736 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 37 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 31,817 | 33K | 11.9M | 1,760.8M | $882.40 | $4,754.17 | $2,828.75 |
| deepseek-v4-flash-free | 13,423 | 33.0M | 3.1M | 1,066.4M | $506.32 | $2,879.50 | $1,867.81 |
| claude-sonnet-4-5 | 16,197 | 43K | 4.0M | 649.4M | $361.08 | $1,753.41 | $1,020.63 |
| claude-opus-4-0 | 1,596 | 15K | 412K | 115.1M | $339.25 | $1,554.41 | $0.00 |
| claude-sonnet-4-5 | 5,002 | 56K | 2.2M | 344.8M | $261.56 | $931.21 | $548.86 |
| gpt-5.5 | 11,854 | 34.5M | 2.0M | 519.5M | $256.72 | $1,402.68 | $1,159.51 |
| claude-haiku-4-5 | 23,029 | 36K | 5.0M | 1,191.9M | $146.01 | $858.18 | $2,052.30 |
| claude-sonnet-4-0 | 3,361 | 33K | 970K | 210.0M | $136.41 | $567.02 | $310.66 |
| claude-opus-4-6 | 474 | 537 | 204K | 44.0M | $106.07 | $595.22 | $0.00 |
| gpt-5.4 | 2,944 | 10.4M | 585K | 137.1M | $74.16 | $257.23 | $288.13 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 991 | 5.0M | 113K | 36.6M | $2.87 | $68.78 | $102.59 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **111,392** | **86.0M** | **30.9M** | **6,137.6M** | **$3,129.96** | **$15,881.65** | **$10,283.84** |

_6,418.2M total tokens processed. 95.6% cache hit rate._

_$26,165.48 total saved ($15,881.65 caching + $10,283.84 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 44,174 | 46K | 17.4M | 2,359.7M | $1,222.80 | $6,371.23 | $3,879.27 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 13,423 | 33.0M | 3.1M | 1,066.4M | $506.32 | $2,879.50 | $1,867.81 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,197 | 43K | 4.0M | 649.4M | $361.08 | $1,753.41 | $1,020.63 |
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
| **Total** | **132,944** | **87.5M** | **39.3M** | **7,447.7M** | **$4,177.11** | **$20,812.99** | **$12,194.69** |

_7,801.5M total tokens processed. 95.5% cache hit rate._

_$33,007.68 total saved ($20,812.99 caching + $12,194.69 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-05 19:53 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
