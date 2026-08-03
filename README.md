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
| Screen time (Linux) | 24h | 167.8h | 564.6h | ~7334h* |
| Interactive human attention | 3.4h | 26.1h | 30.3h | 146.5h |
| Interactive AI generation | 4.6h | 37.9h | 44.8h | 127.3h |
| Worker-classified human attention | 0.2h | 2.8h | 2.8h | 27.6h |
| Worker/headless AI generation | 8.7h | 74.3h | 644.8h | 1103.7h |
| Additive observed work | 16.9h | 140.3h | 722.0h | 1,398.7h |
| Interactive sessions | 6 | 39 | 44 | 404 |
| Worker sessions | 271 | 1,605 | 4,958 | 9,662 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 67 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 98,229 | 105K | 35.8M | 7,396.9M | $3,552.49 | $19,971.89 | $11,025.86 |
| claude-opus-4-6 | 8,633 | 9K | 2.9M | 734.3M | $1,829.13 | $9,913.40 | $0.00 |
| gpt-5.6-sol | 11,232 | 53.7M | 2.4M | 850.0M | $824.27 | $2,295.04 | $1,809.73 |
| deepseek-v4-flash-free | 12,237 | 27.7M | 2.5M | 1,045.2M | $466.99 | $2,822.12 | $1,738.66 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| claude-sonnet-4-5 | 2,074 | 25K | 681K | 144.3M | $106.97 | $389.77 | $214.45 |
| claude-sonnet-4-5 | 2,559 | 6K | 626K | 98.1M | $53.74 | $264.99 | $155.46 |
| gpt-5.5 | 1,591 | 4.3M | 257K | 58.6M | $30.75 | $158.46 | $138.20 |
| claude-haiku-4-5 | 3,885 | 14K | 754K | 218.8M | $27.92 | $157.55 | $364.48 |
| gpt-5.6-terra | 1,048 | 3.6M | 82K | 24.1M | $17.04 | $65.15 | $78.09 |
| gpt-5.6-luna | 392 | 3.1M | 23K | 4.5M | $3.87 | $12.19 | $44.04 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 519 | 1.2M | 82K | 25.5M | $1.41 | $47.95 | $43.59 |
| **Total** | **146,613** | **110.8M** | **47.2M** | **10,840.2M** | **$7,040.23** | **$36,547.51** | **$16,099.77** |

_11,263.2M total tokens processed. 96.2% cache hit rate._

_$52,647.28 total saved ($36,547.51 caching + $16,099.77 model routing vs all-Opus)._

_Model savings are modest because ~96.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 141,415 | 150K | 52.9M | 9,712.6M | $4,751.32 | $26,224.21 | $14,832.28 |
| claude-opus-4-6 | 9,101 | 9K | 3.1M | 778.3M | $1,933.88 | $10,507.33 | $0.00 |
| deepseek-v4-flash-free | 24,207 | 56.7M | 5.3M | 1,995.7M | $917.50 | $5,388.59 | $3,399.82 |
| gpt-5.6-sol | 11,232 | 53.7M | 2.4M | 850.0M | $824.27 | $2,295.04 | $1,809.73 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 26,238 | 50K | 5.6M | 1,376.1M | $169.85 | $990.82 | $2,357.43 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| gpt-5.6-terra | 1,048 | 3.6M | 82K | 24.1M | $17.04 | $65.15 | $78.09 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.6-luna | 392 | 3.1M | 23K | 4.5M | $3.87 | $12.19 | $44.04 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **271,931** | **188.4M** | **84.7M** | **17,901.4M** | **$11,029.91** | **$56,415.74** | **$27,602.64** |

_18,658.0M total tokens processed. 95.9% cache hit rate._

_$84,018.38 total saved ($56,415.74 caching + $27,602.64 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-03 10:51 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
