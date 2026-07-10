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
| User AI session hours | 1.5h | 32.6h | 101.1h | 151.5h |
| AI worker hours | 23.7h | 180.4h | 502.6h | 603.4h |
| AI concurrency hours | 26.3h | 242.8h | 678.2h | 867.4h |
| Interactive sessions | 1 | 67 | 241 | 344 |
| Worker sessions | 18 | 181 | 512 | 849 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 42 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 47,079 | 49K | 17.6M | 2,450.3M | $1,269.55 | $6,615.81 | $3,999.34 |
| deepseek-v4-flash-free | 13,736 | 34.8M | 3.1M | 1,096.7M | $520.32 | $2,961.19 | $1,926.02 |
| claude-opus-4-6 | 1,896 | 2K | 769K | 137.2M | $348.87 | $1,853.21 | $0.00 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 5,573 | 63K | 2.4M | 385.1M | $288.85 | $1,039.99 | $607.05 |
| gpt-5.5 | 10,643 | 30.3M | 1.8M | 453.2M | $225.73 | $1,223.66 | $1,018.14 |
| claude-haiku-4-5 | 23,871 | 37K | 5.2M | 1,241.5M | $151.59 | $893.89 | $2,133.66 |
| gpt-5.4 | 4,882 | 17.7M | 1.0M | 220.0M | $123.31 | $412.64 | $481.23 |
| claude-opus-4-0 | 386 | 3K | 105K | 31.4M | $95.88 | $424.92 | $0.00 |
| claude-sonnet-4-0 | 1,550 | 15K | 421K | 97.7M | $61.91 | $263.88 | $142.77 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.5-fast | 183 | 1.0M | 44K | 22.3M | $9.17 | $60.30 | $42.64 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **125,385** | **89.7M** | **36.4M** | **6,754.1M** | **$3,450.82** | **$17,481.63** | **$11,360.43** |

_7,059.2M total tokens processed. 95.7% cache hit rate._

_$28,842.05 total saved ($17,481.63 caching + $11,360.43 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 63,060 | 66K | 24.5M | 3,238.5M | $1,706.61 | $8,744.01 | $5,359.99 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 15,629 | 39.3M | 3.6M | 1,254.0M | $594.53 | $3,385.99 | $2,198.20 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-6 | 1,896 | 2K | 769K | 137.2M | $348.87 | $1,853.21 | $0.00 |
| claude-sonnet-4-5 | 5,694 | 64K | 2.4M | 394.3M | $295.26 | $1,064.82 | $621.12 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-haiku-4-5 | 23,903 | 37K | 5.2M | 1,242.5M | $151.75 | $894.63 | $2,135.55 |
| gpt-5.4 | 5,079 | 18.3M | 1.0M | 231.1M | $128.36 | $433.39 | $500.26 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **159,584** | **101.8M** | **48.4M** | **8,820.1M** | **$5,094.87** | **$25,348.29** | **$14,401.64** |

_9,236.6M total tokens processed. 95.5% cache hit rate._

_$39,749.93 total saved ($25,348.29 caching + $14,401.64 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-10 05:06 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
