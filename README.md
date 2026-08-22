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
| Screen time (Linux) | 24h | 83.2h | 490.7h | ~7297h* |
| Interactive human attention | 0.0h | 13.1h | 67.3h | 67.3h |
| Interactive AI generation | 0.3h | 51.1h | 187.8h | 187.8h |
| Worker-classified human attention | 0.0h | 2.9h | 8.8h | 8.8h |
| Worker/headless AI generation | 2.0h | 39.5h | 249.4h | 948.7h |
| Additive observed work | 2.3h | 105.8h | 511.5h | 1,210.9h |
| Interactive sessions | 1 | 19 | 87 | 87 |
| Worker sessions | 358 | 1,527 | 5,430 | 9,261 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 51 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 46,145 | 50K | 16.9M | 6,073.3M | $2,914.43 | $16,398.09 | $8,304.92 |
| claude-opus-4-6 | 2,762 | 3K | 969K | 284.9M | $663.56 | $3,846.82 | $0.00 |
| gpt-5.6-sol | 6,010 | 29.9M | 1.3M | 539.9M | $496.17 | $1,457.87 | $1,087.22 |
| gpt-5.6-terra | 3,561 | 17.9M | 764K | 168.5M | $86.24 | $455.10 | $464.12 |
| deepseek-v4-flash-free | 1,533 | 4.7M | 360K | 132.8M | $63.68 | $358.72 | $237.67 |
| claude-haiku-4-5 | 2,818 | 15K | 543K | 159.2M | $21.14 | $114.66 | $264.92 |
| gpt-5.6-luna | 2,617 | 26.3M | 182K | 37.2M | $6.78 | $100.44 | $371.46 |
| **Total** | **65,446** | **79.0M** | **21.0M** | **7,396.1M** | **$4,252.00** | **$22,731.70** | **$10,730.30** |

_7,734.7M total tokens processed. 95.6% cache hit rate._

_$33,462.00 total saved ($22,731.70 caching + $10,730.30 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 132,703 | 142K | 48.2M | 11,638.8M | $5,650.97 | $31,424.77 | $16,866.28 |
| claude-opus-4-6 | 10,483 | 11K | 3.5M | 930.7M | $2,276.80 | $12,564.56 | $0.00 |
| gpt-5.6-sol | 13,075 | 62.5M | 2.8M | 1,059.9M | $1,001.75 | $2,861.87 | $2,191.77 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| gpt-5.6-terra | 3,832 | 18.9M | 806K | 179.6M | $91.08 | $485.11 | $491.44 |
| claude-haiku-4-5 | 4,852 | 20K | 951K | 273.4M | $34.32 | $196.86 | $456.11 |
| gpt-5.6-luna | 2,617 | 26.3M | 182K | 37.2M | $6.78 | $100.44 | $371.46 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **202,832** | **176.8M** | **64.6M** | **16,365.1M** | **$10,186.86** | **$53,467.83** | **$24,303.81** |

_17,063.5M total tokens processed. 95.9% cache hit rate._

_$77,771.64 total saved ($53,467.83 caching + $24,303.81 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-22 20:33 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
