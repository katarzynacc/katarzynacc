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
| Screen time (Linux) | 24h | 107.2h | 490.8h | ~7310h* |
| Interactive human attention | 0.0h | 10.3h | 63.8h | 67.3h |
| Interactive AI generation | 0.1h | 49.2h | 182.9h | 187.9h |
| Worker-classified human attention | 0.0h | 2.9h | 8.8h | 8.8h |
| Worker/headless AI generation | 11.0h | 39.9h | 257.9h | 959.8h |
| Additive observed work | 11.1h | 101.5h | 511.6h | 1,222.0h |
| Interactive sessions | 1 | 18 | 85 | 87 |
| Worker sessions | 213 | 1,357 | 5,295 | 9,302 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 52 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 45,705 | 50K | 16.8M | 6,045.3M | $2,898.08 | $16,322.42 | $8,264.03 |
| claude-opus-4-6 | 2,754 | 3K | 966K | 284.9M | $661.39 | $3,846.82 | $0.00 |
| gpt-5.6-sol | 6,010 | 29.9M | 1.3M | 539.9M | $496.17 | $1,457.87 | $1,087.22 |
| gpt-5.6-terra | 3,561 | 17.9M | 764K | 168.5M | $86.24 | $455.10 | $464.12 |
| deepseek-v4-flash-free | 1,533 | 4.7M | 360K | 132.8M | $63.68 | $358.72 | $237.67 |
| claude-haiku-4-5 | 2,818 | 15K | 543K | 159.2M | $21.14 | $114.66 | $264.92 |
| gpt-5.6-luna | 2,633 | 26.4M | 182K | 37.2M | $6.81 | $100.71 | $373.37 |
| **Total** | **65,014** | **79.2M** | **20.9M** | **7,368.2M** | **$4,233.51** | **$22,656.30** | **$10,691.32** |

_7,705.0M total tokens processed. 95.6% cache hit rate._

_$33,347.62 total saved ($22,656.30 caching + $10,691.32 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 133,410 | 143K | 48.5M | 11,712.6M | $5,682.34 | $31,624.24 | $16,970.34 |
| claude-opus-4-6 | 10,483 | 11K | 3.5M | 930.7M | $2,276.80 | $12,564.56 | $0.00 |
| gpt-5.6-sol | 13,075 | 62.5M | 2.8M | 1,059.9M | $1,001.75 | $2,861.87 | $2,191.77 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| gpt-5.6-terra | 3,832 | 18.9M | 806K | 179.6M | $91.08 | $485.11 | $491.44 |
| claude-haiku-4-5 | 4,852 | 20K | 951K | 273.4M | $34.32 | $196.86 | $456.11 |
| gpt-5.6-luna | 2,633 | 26.4M | 182K | 37.2M | $6.81 | $100.71 | $373.37 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **203,555** | **176.9M** | **64.9M** | **16,439.0M** | **$10,218.26** | **$53,667.56** | **$24,409.78** |

_17,139.4M total tokens processed. 95.9% cache hit rate._

_$78,077.35 total saved ($53,667.56 caching + $24,409.78 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-23 04:33 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
