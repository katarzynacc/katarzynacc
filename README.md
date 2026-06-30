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
| Screen time (Linux) | 24h | 55.2h | 144.6h | ~1,862h* |
| User AI session hours | 4.2h | 24.1h | 107.3h | 108.0h |
| AI worker hours | 14.8h | 141.9h | 321.5h | 359.7h |
| AI concurrency hours | 21.9h | 182.4h | 503.6h | 545.0h |
| Interactive sessions | 18 | 86 | 244 | 253 |
| Worker sessions | 13 | 131 | 543 | 630 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 33 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 31,233 | 32K | 12.5M | 1,727.2M | $883.63 | $4,663.71 | $2,823.61 |
| claude-opus-4-0 | 2,800 | 26K | 776K | 216.6M | $622.44 | $2,925.02 | $0.00 |
| deepseek-v4-flash-free | 9,326 | 21.5M | 2.2M | 734.3M | $345.62 | $1,982.78 | $1,275.93 |
| claude-sonnet-4-0 | 7,091 | 70K | 2.2M | 498.4M | $311.25 | $1,345.76 | $732.47 |
| claude-sonnet-4-5 | 4,160 | 46K | 1.8M | 288.9M | $204.77 | $780.09 | $456.69 |
| claude-sonnet-4-5 | 8,526 | 23K | 2.1M | 346.7M | $195.73 | $936.17 | $544.71 |
| gpt-5.5 | 7,524 | 22.5M | 1.3M | 346.7M | $169.76 | $936.17 | $767.39 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-6 | 261 | 308 | 115K | 23.3M | $60.53 | $315.51 | $0.00 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 507 | 3.9M | 42K | 10.6M | $1.51 | $19.91 | $61.01 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **97,223** | **60.5M** | **28.8M** | **5,527.8M** | **$3,059.06** | **$15,215.50** | **$9,011.30** |

_5,782.9M total tokens processed. 95.6% cache hit rate._

_$24,226.80 total saved ($15,215.50 caching + $9,011.30 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 38,198 | 40K | 15.5M | 2,055.6M | $1,070.91 | $5,550.13 | $3,399.54 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 9,326 | 21.5M | 2.2M | 734.3M | $345.62 | $1,982.78 | $1,275.93 |
| claude-sonnet-4-5 | 4,160 | 46K | 1.8M | 288.9M | $204.77 | $780.09 | $456.69 |
| claude-sonnet-4-5 | 8,526 | 23K | 2.1M | 346.7M | $195.73 | $936.17 | $544.71 |
| gpt-5.5 | 7,524 | 22.5M | 1.3M | 346.7M | $169.76 | $936.17 | $767.39 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-6 | 261 | 308 | 115K | 23.3M | $60.53 | $315.51 | $0.00 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 507 | 3.9M | 42K | 10.6M | $1.51 | $19.91 | $61.01 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **108,105** | **60.5M** | **33.0M** | **6,158.3M** | **$3,485.83** | **$17,217.39** | **$9,982.60** |

_6,447.7M total tokens processed. 95.5% cache hit rate._

_$27,199.98 total saved ($17,217.39 caching + $9,982.60 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-06-30 23:05 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
