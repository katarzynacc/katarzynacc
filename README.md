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
| Screen time (Linux) | 23.9h | 167.8h | 671h | ~7486h* |
| Interactive human attention | 4.4h | 12.3h | 50.0h | 50.0h |
| Interactive AI generation | 12.0h | 52.2h | 130.5h | 130.5h |
| Worker-classified human attention | 0.0h | 0.9h | 5.8h | 5.8h |
| Worker/headless AI generation | 5.6h | 42.6h | 311.7h | 895.4h |
| Additive observed work | 22.0h | 108.1h | 497.0h | 1,080.8h |
| Interactive sessions | 6 | 9 | 68 | 68 |
| Worker sessions | 399 | 1,300 | 4,779 | 7,696 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 43 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 57,931 | 63K | 21.3M | 6,514.3M | $3,103.78 | $17,588.87 | $9,101.02 |
| claude-opus-4-6 | 4,102 | 4K | 1.4M | 382.3M | $1,036.74 | $5,162.35 | $0.00 |
| gpt-5.6-sol | 8,366 | 44.2M | 1.9M | 721.4M | $699.69 | $1,948.00 | $1,511.90 |
| deepseek-v4-flash-free | 4,313 | 9.7M | 892K | 387.3M | $170.75 | $1,045.78 | $635.15 |
| gpt-5.6-terra | 3,161 | 15.0M | 656K | 156.5M | $94.36 | $422.64 | $407.81 |
| gpt-5.6-luna | 1,555 | 14.0M | 131K | 30.7M | $19.62 | $82.95 | $212.86 |
| claude-haiku-4-5 | 2,437 | 13K | 452K | 130.6M | $18.00 | $94.05 | $217.81 |
| **Total** | **81,865** | **83.1M** | **26.8M** | **8,323.4M** | **$5,142.94** | **$26,344.64** | **$12,086.56** |

_8,679.0M total tokens processed. 95.9% cache hit rate._

_$38,431.20 total saved ($26,344.64 caching + $12,086.56 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 120,717 | 129K | 43.7M | 10,081.1M | $4,878.69 | $27,218.99 | $14,721.02 |
| claude-opus-4-6 | 9,645 | 10K | 3.3M | 838.3M | $2,059.06 | $11,318.23 | $0.00 |
| gpt-5.6-sol | 12,569 | 60.2M | 2.7M | 996.4M | $949.07 | $2,690.40 | $2,080.97 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 3,350 | 15.8M | 691K | 165.5M | $99.26 | $446.92 | $429.94 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,250 | 16K | 824K | 235.6M | $30.03 | $169.69 | $393.48 |
| gpt-5.6-luna | 1,555 | 14.0M | 131K | 30.7M | $19.62 | $82.95 | $212.86 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **187,356** | **159.0M** | **59.3M** | **14,593.2M** | **$9,160.89** | **$47,761.40** | **$21,765.03** |

_15,201.8M total tokens processed. 96% cache hit rate._

_$69,526.43 total saved ($47,761.40 caching + $21,765.03 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-14 18:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
