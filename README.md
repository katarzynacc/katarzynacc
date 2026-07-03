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
| Screen time (Linux) | 4.7h | 59.9h | 84.2h | ~1,351h* |
| User AI session hours | 4.8h | 33.9h | 106.9h | 118.9h |
| AI worker hours | 38.9h | 196.0h | 371.2h | 427.5h |
| AI concurrency hours | 45.7h | 250.4h | 548.1h | 629.0h |
| Interactive sessions | 9 | 109 | 250 | 278 |
| Worker sessions | 27 | 171 | 525 | 677 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 35 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 32,173 | 33K | 12.5M | 1,784.3M | $903.21 | $4,817.67 | $2,894.83 |
| claude-opus-4-0 | 2,800 | 26K | 776K | 216.6M | $622.44 | $2,925.02 | $0.00 |
| deepseek-v4-flash-free | 11,140 | 26.4M | 2.6M | 885.1M | $417.88 | $2,389.95 | $1,539.96 |
| claude-sonnet-4-0 | 6,425 | 63K | 1.9M | 446.0M | $281.52 | $1,204.30 | $655.83 |
| claude-sonnet-4-5 | 11,117 | 31K | 2.7M | 437.2M | $247.88 | $1,180.62 | $687.91 |
| gpt-5.5 | 10,196 | 30.2M | 1.7M | 455.6M | $224.93 | $1,230.36 | $1,016.39 |
| claude-sonnet-4-5 | 4,408 | 49K | 1.9M | 305.2M | $219.10 | $824.05 | $482.66 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 468 | 527 | 201K | 43.9M | $104.76 | $593.93 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 652 | 4.3M | 58K | 16.7M | $1.88 | $31.43 | $72.37 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **105,174** | **73.5M** | **30.3M** | **5,925.8M** | **$3,287.42** | **$16,507.73** | **$9,699.45** |

_6,199.8M total tokens processed. 95.6% cache hit rate._

_$26,207.18 total saved ($16,507.73 caching + $9,699.45 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 40,704 | 42K | 16.3M | 2,199.7M | $1,138.31 | $5,939.45 | $3,620.35 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 11,140 | 26.4M | 2.6M | 885.1M | $417.88 | $2,389.95 | $1,539.96 |
| claude-sonnet-4-5 | 11,117 | 31K | 2.7M | 437.2M | $247.88 | $1,180.62 | $687.91 |
| gpt-5.5 | 10,196 | 30.2M | 1.7M | 455.6M | $224.93 | $1,230.36 | $1,016.39 |
| claude-sonnet-4-5 | 4,408 | 49K | 1.9M | 305.2M | $219.10 | $824.05 | $482.66 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 468 | 527 | 201K | 43.9M | $104.76 | $593.93 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 652 | 4.3M | 58K | 16.7M | $1.88 | $31.43 | $72.37 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **118,288** | **73.6M** | **35.4M** | **6,695.8M** | **$3,791.74** | **$18,886.43** | **$10,896.98** |

_7,010.8M total tokens processed. 95.5% cache hit rate._

_$29,783.40 total saved ($18,886.43 caching + $10,896.98 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-03 06:15 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
