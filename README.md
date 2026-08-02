# Kasia CC

![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
>
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | Yesterday | Prior 7 Days | Prior 28 Days | Prior 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 23.9h | 167.8h | 541.1h | ~7318h* |
| Interactive human attention | 3.3h | 23.4h | 26.9h | 143.1h |
| Interactive AI generation | 3.3h | 35.1h | 40.2h | 122.7h |
| Worker-classified human attention | 0.8h | 2.7h | 2.7h | 27.4h |
| Worker/headless AI generation | 17.7h | 68.5h | 658.8h | 1095.0h |
| Additive observed work | 25.1h | 128.8h | 727.7h | 1,381.7h |
| Interactive sessions | 3 | 37 | 39 | 399 |
| Worker sessions | 385 | 1,641 | 4,957 | 9,490 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 66 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 98,737 | 105K | 35.7M | 7,267.7M | $3,510.38 | $19,622.83 | $10,868.30 |
| claude-opus-4-6 | 8,632 | 9K | 2.9M | 734.3M | $1,828.86 | $9,913.40 | $0.00 |
| gpt-5.6-sol | 11,232 | 53.7M | 2.4M | 850.0M | $824.27 | $2,295.04 | $1,809.73 |
| deepseek-v4-flash-free | 12,307 | 28.2M | 2.5M | 1,050.8M | $469.63 | $2,837.39 | $1,752.64 |
| claude-sonnet-4-5 | 2,374 | 29K | 871K | 166.5M | $131.97 | $449.81 | $252.54 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| claude-sonnet-4-5 | 5,232 | 12K | 1.3M | 222.0M | $117.10 | $599.47 | $346.33 |
| gpt-5.5 | 1,873 | 5.2M | 305K | 76.4M | $38.39 | $206.30 | $173.14 |
| claude-haiku-4-5 | 3,591 | 13K | 695K | 203.9M | $26.05 | $146.86 | $339.20 |
| gpt-5.6-terra | 1,048 | 3.6M | 82K | 24.1M | $17.04 | $65.15 | $78.09 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.6-luna | 273 | 1.9M | 19K | 3.8M | $2.60 | $10.36 | $29.51 |
| gpt-5.4-mini | 601 | 1.4M | 92K | 31.0M | $1.67 | $58.25 | $51.71 |
| **Total** | **150,114** | **111.3M** | **48.1M** | **10,870.4M** | **$7,093.61** | **$36,653.85** | **$16,188.42** |

_11,301.9M total tokens processed. 96.2% cache hit rate._

_$52,842.27 total saved ($36,653.85 caching + $16,188.42 model routing vs all-Opus)._

_Model savings are modest because ~96.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 139,524 | 148K | 52.1M | 9,471.0M | $4,650.58 | $25,571.92 | $14,494.29 |
| claude-opus-4-6 | 9,100 | 9K | 3.1M | 778.3M | $1,933.61 | $10,507.33 | $0.00 |
| deepseek-v4-flash-free | 23,861 | 55.5M | 5.2M | 1,966.0M | $901.58 | $5,308.40 | $3,344.25 |
| gpt-5.6-sol | 11,232 | 53.7M | 2.4M | 850.0M | $824.27 | $2,295.04 | $1,809.73 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 25,944 | 49K | 5.6M | 1,361.2M | $167.98 | $980.13 | $2,332.15 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| gpt-5.6-terra | 1,048 | 3.6M | 82K | 24.1M | $17.04 | $65.15 | $78.09 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| gpt-5.6-luna | 273 | 1.9M | 19K | 3.8M | $2.60 | $10.36 | $29.51 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **269,280** | **186.1M** | **83.7M** | **17,614.6M** | **$10,909.84** | **$55,670.74** | **$27,169.27** |

_18,363.1M total tokens processed. 95.9% cache hit rate._

_$82,840.00 total saved ($55,670.74 caching + $27,169.27 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-08-02 12:19 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
