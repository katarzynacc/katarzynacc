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
| Worker sessions | 250 | 1,044 | 4,416 | 6,994 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 40 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 69,691 | 75K | 25.2M | 6,643.5M | $3,131.48 | $17,937.70 | $9,487.48 |
| claude-opus-4-6 | 7,371 | 8K | 2.4M | 681.3M | $1,658.66 | $9,198.00 | $0.00 |
| gpt-5.6-sol | 11,060 | 54.1M | 2.4M | 918.5M | $867.32 | $2,479.96 | $1,898.94 |
| deepseek-v4-flash-free | 6,526 | 12.9M | 1.2M | 570.0M | $245.97 | $1,539.27 | $917.17 |
| gpt-5.6-terra | 1,954 | 8.7M | 332K | 77.7M | $50.12 | $209.90 | $217.99 |
| claude-sonnet-4-5 | 838 | 10K | 258K | 62.2M | $44.60 | $168.18 | $90.41 |
| claude-haiku-4-5 | 2,323 | 13K | 427K | 124.4M | $17.22 | $89.59 | $207.25 |
| gpt-5.6-luna | 983 | 7.6M | 77K | 24.1M | $11.49 | $65.22 | $125.57 |
| **Total** | **100,746** | **83.6M** | **32.5M** | **9,102.1M** | **$6,026.86** | **$31,687.82** | **$12,944.82** |

_9,456.4M total tokens processed. 96.3% cache hit rate._

_$44,632.64 total saved ($31,687.82 caching + $12,944.82 model routing vs all-Opus)._

_Model savings are modest because ~96.3% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 115,670 | 124K | 41.8M | 8,987.2M | $4,357.42 | $24,265.47 | $13,296.94 |
| claude-opus-4-6 | 9,385 | 10K | 3.2M | 816.7M | $2,009.78 | $11,025.48 | $0.00 |
| gpt-5.6-sol | 12,281 | 58.7M | 2.6M | 971.4M | $924.61 | $2,623.05 | $2,029.58 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| gpt-5.6-terra | 2,093 | 9.2M | 359K | 84.1M | $53.49 | $227.19 | $233.14 |
| claude-haiku-4-5 | 4,136 | 16K | 800K | 229.4M | $29.25 | $165.23 | $382.92 |
| gpt-5.6-luna | 983 | 7.6M | 77K | 24.1M | $11.49 | $65.22 | $125.57 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **179,818** | **144.6M** | **56.9M** | **13,358.5M** | **$8,511.20** | **$44,205.85** | **$19,994.91** |

_13,905.4M total tokens processed. 96.1% cache hit rate._

_$64,200.77 total saved ($44,205.85 caching + $19,994.91 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-11 15:01 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
