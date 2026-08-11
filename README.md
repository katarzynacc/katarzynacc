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
| Screen time (Linux) | 24h | 167.8h | 671.1h | ~7448h* |
| Interactive human attention | 0.0h | 7.5h | 40.4h | 40.4h |
| Interactive AI generation | 1.4h | 48.4h | 100.5h | 100.5h |
| Worker-classified human attention | 0.0h | 2.0h | 5.2h | 5.2h |
| Worker/headless AI generation | 0.5h | 86.3h | 368.6h | 875.3h |
| Additive observed work | 1.9h | 144.2h | 513.8h | 1,020.5h |
| Interactive sessions | 1 | 16 | 61 | 61 |
| Worker sessions | 280 | 1,074 | 4,446 | 7,024 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 40 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 69,569 | 75K | 25.2M | 6,672.1M | $3,142.93 | $18,014.88 | $9,524.74 |
| claude-opus-4-6 | 7,336 | 8K | 2.4M | 679.1M | $1,651.94 | $9,168.45 | $0.00 |
| gpt-5.6-sol | 10,813 | 53.2M | 2.4M | 904.3M | $854.11 | $2,441.68 | $1,868.44 |
| deepseek-v4-flash-free | 6,341 | 12.6M | 1.2M | 560.0M | $241.11 | $1,512.06 | $898.87 |
| gpt-5.6-terra | 2,016 | 8.9M | 352K | 87.2M | $53.77 | $235.63 | $233.31 |
| claude-sonnet-4-5 | 838 | 10K | 258K | 62.2M | $44.60 | $168.18 | $90.41 |
| claude-haiku-4-5 | 2,323 | 13K | 427K | 124.4M | $17.22 | $89.59 | $207.25 |
| gpt-5.6-luna | 1,006 | 7.9M | 78K | 24.2M | $11.79 | $65.44 | $128.90 |
| **Total** | **100,242** | **82.8M** | **32.4M** | **9,113.8M** | **$6,017.47** | **$31,695.90** | **$12,951.92** |

_9,467.9M total tokens processed. 96.3% cache hit rate._

_$44,647.82 total saved ($31,695.90 caching + $12,951.92 model routing vs all-Opus)._

_Model savings are modest because ~96.3% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 115,924 | 124K | 41.9M | 9,041.7M | $4,380.22 | $24,412.81 | $13,371.40 |
| claude-opus-4-6 | 9,385 | 10K | 3.2M | 816.7M | $2,009.78 | $11,025.48 | $0.00 |
| gpt-5.6-sol | 12,281 | 58.7M | 2.6M | 971.4M | $924.61 | $2,623.05 | $2,029.58 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| gpt-5.6-terra | 2,203 | 9.7M | 387K | 96.2M | $58.61 | $259.87 | $255.22 |
| claude-haiku-4-5 | 4,136 | 16K | 800K | 229.4M | $29.25 | $165.23 | $382.92 |
| gpt-5.6-luna | 1,006 | 7.9M | 78K | 24.2M | $11.79 | $65.44 | $128.90 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **180,205** | **145.3M** | **57.1M** | **13,425.3M** | **$8,539.42** | **$44,386.10** | **$20,094.78** |

_13,974.3M total tokens processed. 96.1% cache hit rate._

_$64,480.88 total saved ($44,386.10 caching + $20,094.78 model routing vs all-Opus)._

_Model savings are modest because ~96.1% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-08-11 19:02 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
