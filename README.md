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
| Screen time (Linux) | 24h | 167.8h | 517.2h | ~7302h* |
| Interactive human attention | 5.3h | 23.6h | 23.6h | 139.8h |
| Interactive AI generation | 5.0h | 36.9h | 36.9h | 119.5h |
| Worker-classified human attention | 1.7h | 1.9h | 1.9h | 26.7h |
| Worker/headless AI generation | 18.4h | 53.3h | 660.5h | 1077.3h |
| Additive observed work | 29.7h | 114.9h | 722.1h | 1,356.7h |
| Interactive sessions | 7 | 37 | 37 | 397 |
| Worker sessions | 416 | 1,607 | 4,915 | 9,280 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 65 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 99,553 | 106K | 35.8M | 7,068.2M | $3,439.34 | $19,084.23 | $10,637.06 |
| claude-opus-4-6 | 8,624 | 9K | 2.9M | 731.4M | $1,820.74 | $9,875.19 | $0.00 |
| gpt-5.6-sol | 10,371 | 49.0M | 2.2M | 784.4M | $758.62 | $2,118.01 | $1,663.09 |
| deepseek-v4-flash-free | 13,336 | 30.8M | 2.7M | 1,130.4M | $507.67 | $3,052.33 | $1,892.29 |
| claude-sonnet-4-5 | 6,536 | 15K | 1.6M | 269.8M | $144.34 | $728.53 | $420.69 |
| claude-sonnet-4-5 | 2,384 | 29K | 876K | 166.9M | $132.52 | $450.65 | $253.24 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 2,863 | 7.7M | 455K | 128.1M | $60.63 | $345.95 | $274.18 |
| claude-haiku-4-5 | 3,579 | 12K | 693K | 202.8M | $25.83 | $146.05 | $337.46 |
| gpt-5.6-terra | 1,048 | 3.6M | 82K | 24.1M | $17.04 | $65.15 | $78.09 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 640 | 1.5M | 96K | 32.1M | $1.76 | $60.33 | $53.77 |
| gpt-5.6-luna | 133 | 764K | 13K | 2.9M | $1.20 | $7.94 | $13.53 |
| **Total** | **153,281** | **110.6M** | **48.6M** | **10,781.0M** | **$7,035.34** | **$36,383.37** | **$16,110.60** |

_11,210.9M total tokens processed. 96.2% cache hit rate._

_$52,493.97 total saved ($36,383.37 caching + $16,110.60 model routing vs all-Opus)._

_Model savings are modest because ~96.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 137,751 | 146K | 51.4M | 9,123.8M | $4,510.25 | $24,634.36 | $14,036.60 |
| claude-opus-4-6 | 8,962 | 9K | 3.0M | 760.6M | $1,895.69 | $10,269.21 | $0.00 |
| deepseek-v4-flash-free | 23,861 | 55.5M | 5.2M | 1,966.0M | $901.58 | $5,308.40 | $3,344.25 |
| gpt-5.6-sol | 10,371 | 49.0M | 2.2M | 784.4M | $758.62 | $2,118.01 | $1,663.09 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 25,932 | 48K | 5.6M | 1,360.1M | $167.75 | $979.32 | $2,330.41 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| gpt-5.6-terra | 1,048 | 3.6M | 82K | 24.1M | $17.04 | $65.15 | $78.09 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| gpt-5.6-luna | 133 | 764K | 13K | 2.9M | $1.20 | $7.94 | $13.53 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **266,356** | **180.2M** | **82.8M** | **17,182.1M** | **$10,664.31** | **$54,314.79** | **$26,547.22** |

_17,916.4M total tokens processed. 95.9% cache hit rate._

_$80,862.02 total saved ($54,314.79 caching + $26,547.22 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-01 12:19 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
