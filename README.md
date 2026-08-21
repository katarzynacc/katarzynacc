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
| Screen time (Linux) | 5.4h | 83.2h | 490.7h | ~7284h* |
| Interactive human attention | 0.0h | 17.3h | 67.3h | 67.3h |
| Interactive AI generation | 0.0h | 57.1h | 187.6h | 187.6h |
| Worker-classified human attention | 0.0h | 2.9h | 8.8h | 8.8h |
| Worker/headless AI generation | 0.9h | 51.4h | 259.9h | 946.8h |
| Additive observed work | 0.9h | 127.8h | 521.7h | 1,208.6h |
| Interactive sessions | 1 | 21 | 87 | 87 |
| Worker sessions | 173 | 1,498 | 5,270 | 8,986 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 50 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 49,155 | 54K | 18.0M | 6,304.5M | $3,041.85 | $17,022.18 | $8,650.53 |
| claude-opus-4-6 | 2,982 | 3K | 1.0M | 305.5M | $715.80 | $4,125.10 | $0.00 |
| gpt-5.6-sol | 6,010 | 29.9M | 1.3M | 539.9M | $496.17 | $1,457.87 | $1,087.22 |
| gpt-5.6-terra | 3,497 | 17.7M | 750K | 165.6M | $105.99 | $447.12 | $456.45 |
| deepseek-v4-flash-free | 1,533 | 4.7M | 360K | 132.8M | $63.68 | $358.72 | $237.67 |
| gpt-5.6-luna | 2,388 | 23.6M | 173K | 36.3M | $30.92 | $98.20 | $338.14 |
| claude-haiku-4-5 | 2,842 | 16K | 547K | 159.9M | $21.25 | $115.15 | $266.17 |
| **Total** | **68,407** | **76.1M** | **22.2M** | **7,644.7M** | **$4,475.66** | **$23,624.34** | **$11,036.18** |

_7,993.5M total tokens processed. 95.6% cache hit rate._

_$34,660.52 total saved ($23,624.34 caching + $11,036.18 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 131,373 | 141K | 47.8M | 11,531.9M | $5,602.43 | $31,136.22 | $16,710.75 |
| claude-opus-4-6 | 10,482 | 11K | 3.5M | 930.7M | $2,276.51 | $12,564.56 | $0.00 |
| gpt-5.6-sol | 13,075 | 62.5M | 2.8M | 1,059.9M | $1,001.75 | $2,861.87 | $2,191.77 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 3,768 | 18.6M | 792K | 176.7M | $112.05 | $477.14 | $483.77 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,852 | 20K | 951K | 273.4M | $34.32 | $196.86 | $456.11 |
| gpt-5.6-luna | 2,388 | 23.6M | 173K | 36.3M | $30.92 | $98.20 | $338.14 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **201,208** | **173.9M** | **64.1M** | **16,254.4M** | **$10,183.14** | **$53,169.07** | **$24,107.30** |

_16,946.9M total tokens processed. 95.9% cache hit rate._

_$77,276.37 total saved ($53,169.07 caching + $24,107.30 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-21 06:32 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
