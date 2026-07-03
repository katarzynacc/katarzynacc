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
| User AI session hours | 6.8h | 35.3h | 107.1h | 121.3h |
| AI worker hours | 39.6h | 195.6h | 372.9h | 429.3h |
| AI concurrency hours | 49.0h | 251.8h | 549.8h | 633.9h |
| Interactive sessions | 16 | 114 | 256 | 285 |
| Worker sessions | 32 | 175 | 524 | 684 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 35 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 32,021 | 33K | 12.4M | 1,778.6M | $899.42 | $4,802.40 | $2,884.25 |
| claude-opus-4-0 | 2,800 | 26K | 776K | 216.6M | $622.44 | $2,925.02 | $0.00 |
| deepseek-v4-flash-free | 11,521 | 27.2M | 2.7M | 913.1M | $430.87 | $2,465.54 | $1,587.60 |
| claude-sonnet-4-5 | 11,388 | 32K | 2.7M | 446.1M | $253.29 | $1,204.72 | $702.54 |
| claude-sonnet-4-0 | 5,747 | 57K | 1.7M | 395.7M | $252.11 | $1,068.58 | $581.40 |
| gpt-5.5 | 10,293 | 30.5M | 1.7M | 461.1M | $227.41 | $1,245.10 | $1,027.64 |
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
| **Total** | **105,093** | **74.6M** | **30.1M** | **5,912.3M** | **$3,275.10** | **$16,471.17** | **$9,687.95** |

_6,184.5M total tokens processed. 95.6% cache hit rate._

_$26,159.12 total saved ($16,471.17 caching + $9,687.95 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 40,786 | 43K | 16.3M | 2,203.2M | $1,140.15 | $5,948.70 | $3,625.78 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 11,521 | 27.2M | 2.7M | 913.1M | $430.87 | $2,465.54 | $1,587.60 |
| claude-sonnet-4-5 | 11,388 | 32K | 2.7M | 446.1M | $253.29 | $1,204.72 | $702.54 |
| gpt-5.5 | 10,293 | 30.5M | 1.7M | 461.1M | $227.41 | $1,245.10 | $1,027.64 |
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
| **Total** | **119,119** | **74.6M** | **35.6M** | **6,741.6M** | **$3,814.46** | **$19,010.12** | **$10,975.92** |

_7,058.5M total tokens processed. 95.5% cache hit rate._

_$29,986.04 total saved ($19,010.12 caching + $10,975.92 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-03 10:16 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
