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
| Screen time (Linux) | 24h | 167.7h | 671.1h | ~7434h* |
| Interactive human attention | 2.6h | 10.1h | 40.4h | 40.4h |
| Interactive AI generation | 16.6h | 54.4h | 99.1h | 99.1h |
| Worker-classified human attention | 0.3h | 2.4h | 5.2h | 5.2h |
| Worker/headless AI generation | 12.9h | 95.6h | 431.4h | 874.7h |
| Additive observed work | 32.4h | 162.3h | 575.2h | 1,018.6h |
| Interactive sessions | 2 | 20 | 61 | 61 |
| Worker sessions | 322 | 1,099 | 4,438 | 6,833 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 39 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 76,591 | 82K | 27.6M | 7,044.4M | $3,333.75 | $19,020.06 | $10,114.53 |
| claude-opus-4-6 | 7,371 | 8K | 2.4M | 681.3M | $1,658.66 | $9,198.00 | $0.00 |
| gpt-5.6-sol | 11,330 | 55.2M | 2.4M | 931.4M | $881.04 | $2,514.93 | $1,930.32 |
| deepseek-v4-flash-free | 7,527 | 16.4M | 1.5M | 653.7M | $287.58 | $1,765.22 | $1,072.05 |
| claude-sonnet-4-5 | 1,098 | 14K | 355K | 77.7M | $56.35 | $209.88 | $114.78 |
| gpt-5.6-terra | 2,093 | 9.2M | 359K | 84.1M | $53.49 | $227.19 | $233.14 |
| claude-haiku-4-5 | 2,405 | 13K | 451K | 131.8M | $18.06 | $94.95 | $219.53 |
| gpt-5.6-luna | 951 | 7.4M | 76K | 23.9M | $11.19 | $64.58 | $122.24 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| **Total** | **109,394** | **89.3M** | **35.3M** | **9,628.7M** | **$6,302.94** | **$33,094.81** | **$13,817.59** |

_10,005.3M total tokens processed. 96.2% cache hit rate._

_$46,912.39 total saved ($33,094.81 caching + $13,817.59 model routing vs all-Opus)._

_Model savings are modest because ~96.2% of tokens are cache reads, where price differences between models are small._

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
| gpt-5.6-luna | 951 | 7.4M | 76K | 23.9M | $11.19 | $64.58 | $122.24 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **179,786** | **144.3M** | **56.9M** | **13,358.3M** | **$8,510.90** | **$44,205.22** | **$19,991.59** |

_13,905.0M total tokens processed. 96.1% cache hit rate._

_$64,196.81 total saved ($44,205.22 caching + $19,991.59 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-10 13:02 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
