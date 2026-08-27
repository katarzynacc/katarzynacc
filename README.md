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
| Screen time (Linux) | 23.9h | 116.5h | 457.9h | ~7293h* |
| Interactive human attention | 0.6h | 12.9h | 69.0h | 80.2h |
| Interactive AI generation | 1.8h | 23.6h | 188.6h | 211.1h |
| Worker-classified human attention | 1.4h | 8.8h | 17.3h | 17.5h |
| Worker/headless AI generation | 8.9h | 85.6h | 308.9h | 1031.5h |
| Additive observed work | 12.7h | 130.6h | 581.9h | 1,338.3h |
| Interactive sessions | 5 | 15 | 88 | 101 |
| Worker sessions | 440 | 1,512 | 5,538 | 10,324 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 56 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 58,696 | 64K | 22.1M | 7,022.5M | $3,361.13 | $18,960.99 | $9,759.41 |
| claude-opus-4-6 | 4,063 | 4K | 1.4M | 414.8M | $942.68 | $5,600.71 | $0.00 |
| gpt-5.6-sol | 4,854 | 23.2M | 1.0M | 445.4M | $400.77 | $1,202.79 | $877.41 |
| gpt-5.6-terra | 3,870 | 20.4M | 954K | 211.2M | $103.52 | $570.50 | $556.30 |
| claude-opus-4-8 | 196 | 390 | 171K | 26.1M | $95.06 | $353.69 | $0.00 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| deepseek-v4-flash-free | 982 | 3.4M | 249K | 84.4M | $42.38 | $228.08 | $157.30 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| claude-haiku-4-5 | 2,856 | 16K | 551K | 160.9M | $21.46 | $115.91 | $267.99 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 3,101 | 29.5M | 217K | 43.4M | $7.74 | $117.38 | $420.33 |
| **Total** | **80,420** | **88.6M** | **27.2M** | **8,646.4M** | **$5,088.80** | **$27,790.23** | **$12,489.95** |

_9,028.1M total tokens processed. 95.8% cache hit rate._

_$40,280.19 total saved ($27,790.23 caching + $12,489.95 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 149,914 | 161K | 55.0M | 13,266.1M | $6,408.44 | $35,818.50 | $19,225.85 |
| claude-opus-4-6 | 11,815 | 12K | 4.0M | 1,060.6M | $2,563.92 | $14,318.63 | $0.00 |
| gpt-5.6-sol | 13,185 | 63.5M | 2.8M | 1,068.5M | $1,013.17 | $2,884.97 | $2,216.30 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 4,528 | 22.8M | 1.0M | 227.1M | $112.48 | $613.33 | $607.55 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-opus-4-8 | 196 | 390 | 171K | 26.1M | $95.06 | $353.69 | $0.00 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| claude-haiku-4-5 | 4,892 | 20K | 960K | 275.1M | $34.67 | $198.11 | $459.18 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 3,101 | 29.5M | 217K | 43.4M | $7.74 | $117.38 | $420.33 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **224,703** | **196.9M** | **72.7M** | **18,449.7M** | **$11,474.70** | **$60,779.01** | **$27,307.18** |

_19,226.7M total tokens processed. 96% cache hit rate._

_$88,086.19 total saved ($60,779.01 caching + $27,307.18 model routing vs all-Opus)._

_Model savings are modest because ~96% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-08-27 14:28 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
