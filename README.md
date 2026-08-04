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
| Screen time (Linux) | 23.9h | 167.7h | 564.5h | ~7349h* |
| Interactive human attention | 2.6h | 27.3h | 32.9h | 149.1h |
| Interactive AI generation | 7.4h | 41.8h | 52.1h | 134.7h |
| Worker-classified human attention | 0.4h | 3.2h | 3.2h | 28.0h |
| Worker/headless AI generation | 9.8h | 80.6h | 599.7h | 1113.6h |
| Additive observed work | 20.1h | 152.0h | 687.1h | 1,418.8h |
| Interactive sessions | 9 | 43 | 50 | 410 |
| Worker sessions | 436 | 1,777 | 4,989 | 10,013 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 68 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 104,789 | 112K | 38.1M | 8,183.4M | $3,953.91 | $22,095.40 | $12,112.55 |
| claude-opus-4-6 | 9,106 | 9K | 3.0M | 785.9M | $1,937.30 | $10,609.78 | $0.00 |
| gpt-5.6-sol | 11,232 | 53.7M | 2.4M | 850.0M | $824.27 | $2,295.04 | $1,809.73 |
| deepseek-v4-flash-free | 10,933 | 25.0M | 2.2M | 941.2M | $419.74 | $2,541.36 | $1,566.06 |
| gpt-5.4 | 3,980 | 14.8M | 970K | 218.1M | $113.45 | $409.05 | $440.04 |
| claude-sonnet-4-5 | 1,790 | 21K | 568K | 127.2M | $90.05 | $343.49 | $187.03 |
| claude-haiku-4-5 | 3,321 | 14K | 626K | 188.1M | $24.34 | $135.45 | $311.85 |
| gpt-5.6-terra | 1,048 | 3.6M | 82K | 24.1M | $17.04 | $65.15 | $78.09 |
| claude-sonnet-4-5 | 357 | 679 | 80K | 16.5M | $7.96 | $44.55 | $24.63 |
| gpt-5.6-luna | 470 | 3.8M | 26K | 4.9M | $4.71 | $13.40 | $53.54 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 262 | 748K | 36K | 11.1M | $0.69 | $20.90 | $21.49 |
| **Total** | **147,316** | **103.0M** | **48.3M** | **11,350.8M** | **$7,396.28** | **$38,573.57** | **$16,616.02** |

_11,796.0M total tokens processed. 96.2% cache hit rate._

_$55,189.59 total saved ($38,573.57 caching + $16,616.02 model routing vs all-Opus)._

_Model savings are modest because ~96.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 148,965 | 159K | 55.6M | 10,543.5M | $5,176.83 | $28,467.55 | $15,992.24 |
| claude-opus-4-6 | 9,580 | 10K | 3.3M | 829.9M | $2,043.37 | $11,204.99 | $0.00 |
| deepseek-v4-flash-free | 24,379 | 58.1M | 5.4M | 2,009.9M | $926.89 | $5,426.79 | $3,436.99 |
| gpt-5.6-sol | 11,232 | 53.7M | 2.4M | 850.0M | $824.27 | $2,295.04 | $1,809.73 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 26,382 | 51K | 5.6M | 1,381.0M | $170.51 | $994.37 | $2,366.04 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| gpt-5.6-terra | 1,048 | 3.6M | 82K | 24.1M | $17.04 | $65.15 | $78.09 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-luna | 470 | 3.8M | 26K | 4.9M | $4.71 | $13.40 | $53.54 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **280,354** | **190.6M** | **87.7M** | **18,803.5M** | **$11,575.80** | **$59,399.70** | **$28,817.88** |

_19,602.5M total tokens processed. 95.9% cache hit rate._

_$88,217.58 total saved ($59,399.70 caching + $28,817.88 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-04 20:52 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
