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
| User AI session hours | 6.4h | 36.7h | 108.5h | 122.9h |
| AI worker hours | 41.9h | 178.6h | 377.1h | 433.5h |
| AI concurrency hours | 50.9h | 237.1h | 555.4h | 640.8h |
| Interactive sessions | 16 | 116 | 257 | 288 |
| Worker sessions | 32 | 163 | 520 | 686 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 35 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 31,987 | 33K | 12.4M | 1,777.6M | $898.27 | $4,799.62 | $2,881.92 |
| claude-opus-4-0 | 2,800 | 26K | 776K | 216.6M | $622.44 | $2,925.02 | $0.00 |
| deepseek-v4-flash-free | 11,554 | 27.3M | 2.7M | 915.1M | $431.96 | $2,471.01 | $1,591.62 |
| claude-sonnet-4-5 | 11,640 | 32K | 2.8M | 458.4M | $259.34 | $1,237.91 | $721.27 |
| claude-sonnet-4-0 | 5,665 | 56K | 1.7M | 392.1M | $249.14 | $1,058.71 | $575.25 |
| claude-sonnet-4-5 | 4,607 | 52K | 2.0M | 320.6M | $235.30 | $865.71 | $508.11 |
| gpt-5.5 | 10,558 | 31.3M | 1.8M | 478.4M | $234.64 | $1,291.82 | $1,060.75 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 468 | 527 | 201K | 43.9M | $104.76 | $593.93 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 734 | 4.5M | 67K | 22.2M | $2.14 | $41.74 | $80.49 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **105,808** | **75.7M** | **30.3M** | **5,960.1M** | **$3,301.81** | **$16,595.87** | **$9,768.90** |

_6,236.1M total tokens processed. 95.6% cache hit rate._

_$26,364.78 total saved ($16,595.87 caching + $9,768.90 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 40,786 | 43K | 16.3M | 2,203.2M | $1,140.15 | $5,948.70 | $3,625.78 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 11,554 | 27.3M | 2.7M | 915.1M | $431.96 | $2,471.01 | $1,591.62 |
| claude-sonnet-4-5 | 11,640 | 32K | 2.8M | 458.4M | $259.34 | $1,237.91 | $721.27 |
| claude-sonnet-4-5 | 4,607 | 52K | 2.0M | 320.6M | $235.30 | $865.71 | $508.11 |
| gpt-5.5 | 10,558 | 31.3M | 1.8M | 478.4M | $234.64 | $1,291.82 | $1,060.75 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 468 | 527 | 201K | 43.9M | $104.76 | $593.93 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 734 | 4.5M | 67K | 22.2M | $2.14 | $41.74 | $80.49 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **119,950** | **75.8M** | **35.9M** | **6,794.2M** | **$3,845.29** | **$19,147.46** | **$11,065.35** |

_7,115.4M total tokens processed. 95.5% cache hit rate._

_$30,212.81 total saved ($19,147.46 caching + $11,065.35 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-03 14:16 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
