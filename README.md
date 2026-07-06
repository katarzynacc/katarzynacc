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
| Screen time (Linux) | 7h | 4.7h | 84.2h | ~1,351h* |
| User AI session hours | 8.6h | 41.9h | 109.8h | 139.7h |
| AI worker hours | 28.9h | 166.5h | 412.7h | 492.1h |
| AI concurrency hours | 41.4h | 242.1h | 600.2h | 735.7h |
| Interactive sessions | 19 | 107 | 252 | 317 |
| Worker sessions | 46 | 178 | 485 | 764 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 38 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 33,338 | 35K | 12.3M | 1,810.8M | $913.54 | $4,889.32 | $2,916.32 |
| deepseek-v4-flash-free | 13,939 | 34.0M | 3.2M | 1,109.6M | $525.13 | $2,996.08 | $1,936.63 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-0 | 1,486 | 14K | 390K | 110.1M | $325.74 | $1,486.60 | $0.00 |
| claude-sonnet-4-5 | 5,233 | 59K | 2.3M | 364.0M | $274.22 | $982.88 | $576.55 |
| gpt-5.5 | 11,258 | 33.1M | 1.9M | 495.9M | $245.53 | $1,339.04 | $1,109.31 |
| claude-haiku-4-5 | 23,031 | 36K | 5.0M | 1,191.9M | $146.02 | $858.18 | $2,052.32 |
| claude-sonnet-4-0 | 3,115 | 31K | 906K | 195.0M | $125.92 | $526.53 | $288.78 |
| claude-opus-4-6 | 575 | 642 | 235K | 49.5M | $119.47 | $669.49 | $0.00 |
| gpt-5.4 | 3,726 | 13.2M | 732K | 168.0M | $92.48 | $315.07 | $360.19 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 991 | 5.0M | 113K | 36.6M | $2.87 | $68.78 | $102.59 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **114,019** | **88.5M** | **31.6M** | **6,261.6M** | **$3,198.50** | **$16,196.08** | **$10,496.17** |

_6,548.5M total tokens processed. 95.6% cache hit rate._

_$26,692.25 total saved ($16,196.08 caching + $10,496.17 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 46,258 | 48K | 18.1M | 2,446.6M | $1,271.19 | $6,606.06 | $4,024.27 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 13,939 | 34.0M | 3.2M | 1,109.6M | $525.13 | $2,996.08 | $1,936.63 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,233 | 59K | 2.3M | 364.0M | $274.22 | $982.88 | $576.55 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-haiku-4-5 | 23,063 | 36K | 5.0M | 1,192.9M | $146.18 | $858.93 | $2,054.21 |
| claude-opus-4-6 | 575 | 642 | 235K | 49.5M | $119.47 | $669.49 | $0.00 |
| gpt-5.4 | 3,726 | 13.2M | 732K | 168.0M | $92.48 | $315.07 | $360.19 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 991 | 5.0M | 113K | 36.6M | $2.87 | $68.78 | $102.59 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **137,086** | **91.3M** | **40.4M** | **7,652.2M** | **$4,298.10** | **$21,399.03** | **$12,536.54** |

_8,016.4M total tokens processed. 95.5% cache hit rate._

_$33,935.57 total saved ($21,399.03 caching + $12,536.54 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-06 08:09 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
