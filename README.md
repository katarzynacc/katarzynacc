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
| Screen time (Linux) | 0h | 119.9h | 623.1h | ~7498h* |
| Interactive human attention | 2.4h | 19.0h | 59.4h | 59.4h |
| Interactive AI generation | 20.5h | 60.1h | 159.2h | 159.2h |
| Worker-classified human attention | 0.5h | 1.1h | 6.3h | 6.3h |
| Worker/headless AI generation | 8.9h | 54.1h | 287.1h | 928.8h |
| Additive observed work | 32.3h | 134.3h | 511.2h | 1,152.9h |
| Interactive sessions | 11 | 20 | 80 | 80 |
| Worker sessions | 380 | 1,584 | 5,058 | 8,326 |

_Screen time from screen-time-history:daily-observations; collection status: stale. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 46 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 54,172 | 59K | 20.1M | 6,497.3M | $3,097.20 | $17,542.72 | $9,005.17 |
| claude-opus-4-6 | 3,342 | 3K | 1.1M | 332.8M | $914.48 | $4,493.48 | $0.00 |
| gpt-5.6-sol | 7,543 | 39.6M | 1.7M | 685.7M | $646.89 | $1,851.50 | $1,403.82 |
| gpt-5.6-terra | 3,345 | 16.5M | 701K | 159.5M | $100.02 | $430.85 | $431.86 |
| deepseek-v4-flash-free | 2,406 | 6.8M | 557K | 209.7M | $98.47 | $566.33 | $367.21 |
| gpt-5.6-luna | 1,955 | 19.0M | 156K | 34.4M | $25.57 | $93.13 | $279.23 |
| claude-haiku-4-5 | 2,326 | 13K | 435K | 126.5M | $17.48 | $91.15 | $210.84 |
| **Total** | **75,089** | **82.0M** | **24.8M** | **8,046.3M** | **$4,900.11** | **$25,069.17** | **$11,698.12** |

_8,401.9M total tokens processed. 95.8% cache hit rate._

_$36,767.29 total saved ($25,069.17 caching + $11,698.12 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 126,788 | 136K | 46.2M | 10,846.6M | $5,239.61 | $29,285.87 | $15,790.29 |
| claude-opus-4-6 | 9,848 | 10K | 3.3M | 859.3M | $2,107.42 | $11,601.38 | $0.00 |
| gpt-5.6-sol | 13,074 | 62.5M | 2.8M | 1,059.9M | $1,001.70 | $2,861.87 | $2,191.64 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 3,534 | 17.2M | 736K | 168.5M | $104.92 | $455.13 | $453.98 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,251 | 16K | 825K | 235.6M | $30.05 | $169.69 | $393.51 |
| gpt-5.6-luna | 1,955 | 19.0M | 156K | 34.4M | $25.57 | $93.13 | $279.23 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **194,720** | **167.8M** | **62.1M** | **15,450.0M** | **$9,634.43** | **$50,301.29** | **$23,035.41** |

_16,095.8M total tokens processed. 96% cache hit rate._

_$73,336.70 total saved ($50,301.29 caching + $23,035.41 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-17 12:27 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
