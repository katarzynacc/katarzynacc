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
| Screen time (Linux) | 23.9h | 167.8h | 493.2h | ~7286h* |
| Interactive human attention | 7.1h | 18.3h | 20.3h | 134.5h |
| Interactive AI generation | 9.4h | 31.9h | 32.6h | 114.5h |
| Worker-classified human attention | 0.0h | 0.2h | 0.6h | 25.0h |
| Worker/headless AI generation | 11.7h | 47.4h | 688.3h | 1058.9h |
| Additive observed work | 28.2h | 97.8h | 741.7h | 1,327.0h |
| Interactive sessions | 23 | 36 | 43 | 396 |
| Worker sessions | 463 | 1,534 | 4,938 | 9,092 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 64 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 98,626 | 105K | 35.5M | 6,958.5M | $3,387.44 | $18,788.18 | $10,483.90 |
| claude-opus-4-6 | 8,460 | 9K | 2.8M | 713.2M | $1,777.56 | $9,629.51 | $0.00 |
| gpt-5.6-sol | 9,699 | 45.9M | 2.0M | 742.8M | $715.91 | $2,005.61 | $1,567.55 |
| deepseek-v4-flash-free | 13,672 | 31.7M | 2.8M | 1,158.4M | $520.69 | $3,127.79 | $1,941.36 |
| claude-sonnet-4-5 | 7,156 | 17K | 1.7M | 289.9M | $156.25 | $782.82 | $453.10 |
| claude-sonnet-4-5 | 2,498 | 30K | 943K | 175.8M | $141.12 | $474.88 | $268.03 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 3,760 | 10.5M | 603K | 164.1M | $79.65 | $443.18 | $360.36 |
| claude-haiku-4-5 | 3,113 | 10K | 607K | 170.6M | $21.44 | $122.89 | $285.69 |
| gpt-5.6-terra | 1,048 | 3.6M | 82K | 24.1M | $17.04 | $65.15 | $78.09 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 692 | 1.6M | 102K | 35.4M | $1.92 | $66.48 | $58.45 |
| **Total** | **152,938** | **110.5M** | **48.4M** | **10,672.8M** | **$6,944.67** | **$35,955.51** | **$15,983.73** |

_11,099.0M total tokens processed. 96.2% cache hit rate._

_$51,939.24 total saved ($35,955.51 caching + $15,983.73 model routing vs all-Opus)._

_Model savings are modest because ~96.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 136,824 | 145K | 51.0M | 9,014.1M | $4,458.35 | $24,338.31 | $13,883.44 |
| claude-opus-4-6 | 8,797 | 9K | 3.0M | 742.4M | $1,852.25 | $10,023.52 | $0.00 |
| deepseek-v4-flash-free | 23,861 | 55.5M | 5.2M | 1,966.0M | $901.58 | $5,308.40 | $3,344.25 |
| gpt-5.6-sol | 9,699 | 45.9M | 2.0M | 742.8M | $715.91 | $2,005.61 | $1,567.55 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 25,466 | 46K | 5.5M | 1,328.0M | $163.37 | $956.17 | $2,278.64 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| gpt-5.6-terra | 1,048 | 3.6M | 82K | 24.1M | $17.04 | $65.15 | $78.09 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **263,993** | **176.3M** | **82.1M** | **16,977.5M** | **$10,520.68** | **$53,629.58** | **$26,233.22** |

_17,701.6M total tokens processed. 95.9% cache hit rate._

_$79,862.79 total saved ($53,629.58 caching + $26,233.22 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-31 20:02 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
