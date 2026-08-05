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
| Screen time (Linux) | 23.9h | 167.6h | 575.5h | ~7364h* |
| Interactive human attention | 3.3h | 25.4h | 36.2h | 152.3h |
| Interactive AI generation | 19.2h | 57.7h | 71.3h | 153.8h |
| Worker-classified human attention | 1.6h | 4.6h | 4.8h | 29.6h |
| Worker/headless AI generation | 40.9h | 110.6h | 599.0h | 1154.5h |
| Additive observed work | 64.9h | 197.5h | 710.4h | 1,483.6h |
| Interactive sessions | 6 | 41 | 51 | 411 |
| Worker sessions | 338 | 1,665 | 4,859 | 10,131 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 69 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 102,585 | 110K | 37.3M | 8,092.3M | $3,903.85 | $21,849.40 | $11,954.60 |
| claude-opus-4-6 | 9,060 | 9K | 3.1M | 789.2M | $1,946.47 | $10,654.73 | $0.00 |
| gpt-5.6-sol | 11,232 | 53.7M | 2.4M | 850.0M | $824.27 | $2,295.04 | $1,809.73 |
| deepseek-v4-flash-free | 10,275 | 24.0M | 2.1M | 887.8M | $396.52 | $2,397.11 | $1,481.45 |
| gpt-5.4 | 3,112 | 11.7M | 801K | 183.6M | $93.02 | $344.28 | $359.95 |
| claude-sonnet-4-5 | 1,559 | 19K | 490K | 108.0M | $77.40 | $291.82 | $159.35 |
| claude-haiku-4-5 | 3,101 | 14K | 596K | 178.3M | $23.22 | $128.43 | $295.83 |
| gpt-5.6-terra | 1,048 | 3.6M | 82K | 24.1M | $17.04 | $65.15 | $78.09 |
| gpt-5.6-luna | 470 | 3.8M | 26K | 4.9M | $4.71 | $13.40 | $53.54 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 262 | 748K | 36K | 11.1M | $0.69 | $20.90 | $21.49 |
| **Total** | **142,732** | **98.9M** | **47.0M** | **11,129.7M** | **$7,290.01** | **$38,060.26** | **$16,225.04** |

_11,564.5M total tokens processed. 96.2% cache hit rate._

_$54,285.30 total saved ($38,060.26 caching + $16,225.04 model routing vs all-Opus)._

_Model savings are modest because ~96.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 149,864 | 160K | 55.9M | 10,595.9M | $5,205.36 | $28,608.98 | $16,073.94 |
| claude-opus-4-6 | 9,635 | 10K | 3.3M | 838.8M | $2,065.95 | $11,324.22 | $0.00 |
| deepseek-v4-flash-free | 24,414 | 58.4M | 5.4M | 2,012.8M | $928.71 | $5,434.71 | $3,444.07 |
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
| **Total** | **281,343** | **190.8M** | **88.0M** | **18,867.6M** | **$11,628.73** | **$59,668.27** | **$28,906.66** |

_19,669.8M total tokens processed. 95.9% cache hit rate._

_$88,574.94 total saved ($59,668.27 caching + $28,906.66 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-05 10:27 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
