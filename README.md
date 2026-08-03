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
| Interactive sessions | 8 | 41 | 46 | 406 |
| Worker sessions | 404 | 1,738 | 5,091 | 9,795 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 67 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 99,254 | 106K | 36.2M | 7,609.2M | $3,659.05 | $20,545.05 | $11,307.22 |
| claude-opus-4-6 | 8,633 | 9K | 2.9M | 734.3M | $1,829.13 | $9,913.40 | $0.00 |
| gpt-5.6-sol | 11,232 | 53.7M | 2.4M | 850.0M | $824.27 | $2,295.04 | $1,809.73 |
| deepseek-v4-flash-free | 11,482 | 26.3M | 2.3M | 979.8M | $438.89 | $2,645.54 | $1,634.54 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| claude-sonnet-4-5 | 1,990 | 24K | 649K | 138.9M | $101.57 | $375.26 | $206.06 |
| claude-sonnet-4-5 | 1,909 | 4K | 481K | 75.5M | $40.76 | $203.91 | $119.56 |
| claude-haiku-4-5 | 3,885 | 14K | 754K | 218.8M | $27.92 | $157.55 | $364.48 |
| gpt-5.5 | 1,312 | 3.8M | 215K | 48.0M | $26.01 | $129.69 | $116.84 |
| gpt-5.6-terra | 1,048 | 3.6M | 82K | 24.1M | $17.04 | $65.15 | $78.09 |
| gpt-5.6-luna | 461 | 3.7M | 25K | 4.9M | $4.59 | $13.33 | $52.19 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 519 | 1.2M | 82K | 25.5M | $1.41 | $47.95 | $43.59 |
| **Total** | **145,939** | **109.5M** | **47.3M** | **10,948.9M** | **$7,096.29** | **$36,840.86** | **$16,219.52** |

_11,378.3M total tokens processed. 96.2% cache hit rate._

_$53,060.38 total saved ($36,840.86 caching + $16,219.52 model routing vs all-Opus)._

_Model savings are modest because ~96.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 143,385 | 153K | 53.6M | 9,966.8M | $4,880.55 | $26,910.58 | $15,182.52 |
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
| gpt-5.6-luna | 461 | 3.7M | 25K | 4.9M | $4.59 | $13.33 | $52.19 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **273,970** | **189.1M** | **85.5M** | **18,156.0M** | **$11,159.86** | **$57,103.25** | **$27,961.02** |

_18,925.1M total tokens processed. 95.9% cache hit rate._

_$85,064.27 total saved ($57,103.25 caching + $27,961.02 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-03 21:52 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
