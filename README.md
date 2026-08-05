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
| Interactive sessions | 14 | 49 | 59 | 419 |
| Worker sessions | 446 | 1,772 | 4,966 | 10,238 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 69 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 102,535 | 110K | 37.2M | 8,246.0M | $3,970.73 | $22,264.34 | $12,134.34 |
| claude-opus-4-6 | 8,548 | 9K | 2.8M | 746.9M | $1,843.14 | $10,084.04 | $0.00 |
| gpt-5.6-sol | 11,232 | 53.7M | 2.4M | 850.0M | $824.27 | $2,295.04 | $1,809.73 |
| deepseek-v4-flash-free | 9,707 | 21.9M | 1.9M | 836.6M | $370.79 | $2,258.96 | $1,385.67 |
| claude-sonnet-4-5 | 1,559 | 19K | 490K | 108.0M | $77.40 | $291.82 | $159.35 |
| gpt-5.4 | 2,504 | 9.2M | 635K | 150.2M | $74.84 | $281.79 | $289.03 |
| claude-haiku-4-5 | 2,933 | 14K | 551K | 169.9M | $22.09 | $122.39 | $280.72 |
| gpt-5.6-terra | 1,048 | 3.6M | 82K | 24.1M | $17.04 | $65.15 | $78.09 |
| gpt-5.6-luna | 470 | 3.8M | 26K | 4.9M | $4.71 | $13.40 | $53.54 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 231 | 686K | 32K | 10.2M | $0.63 | $19.19 | $19.66 |
| **Total** | **140,795** | **94.2M** | **46.3M** | **11,147.3M** | **$7,208.46** | **$37,696.12** | **$16,221.14** |

_11,581.2M total tokens processed. 96.3% cache hit rate._

_$53,917.26 total saved ($37,696.12 caching + $16,221.14 model routing vs all-Opus)._

_Model savings are modest because ~96.3% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 152,463 | 162K | 56.9M | 10,876.9M | $5,342.62 | $29,367.84 | $16,471.29 |
| claude-opus-4-6 | 9,646 | 10K | 3.3M | 840.0M | $2,070.31 | $11,340.98 | $0.00 |
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
| **Total** | **283,953** | **190.8M** | **89.0M** | **19,149.9M** | **$11,770.35** | **$60,443.90** | **$29,304.02** |

_19,963.3M total tokens processed. 95.9% cache hit rate._

_$89,747.92 total saved ($60,443.90 caching + $29,304.02 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-05 19:28 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
