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
| Interactive sessions | 5 | 8 | 67 | 67 |
| Worker sessions | 382 | 1,283 | 4,762 | 7,679 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 43 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 58,046 | 63K | 21.4M | 6,517.4M | $3,107.23 | $17,597.17 | $9,110.41 |
| claude-opus-4-6 | 4,102 | 4K | 1.4M | 382.3M | $1,036.74 | $5,162.35 | $0.00 |
| gpt-5.6-sol | 8,366 | 44.2M | 1.9M | 721.4M | $699.69 | $1,948.00 | $1,511.90 |
| deepseek-v4-flash-free | 4,313 | 9.7M | 892K | 387.3M | $170.75 | $1,045.78 | $635.15 |
| gpt-5.6-terra | 3,160 | 15.0M | 656K | 156.5M | $94.33 | $422.64 | $407.69 |
| gpt-5.6-luna | 1,541 | 13.8M | 131K | 30.7M | $19.41 | $82.92 | $210.45 |
| claude-haiku-4-5 | 2,437 | 13K | 452K | 130.6M | $18.00 | $94.05 | $217.81 |
| **Total** | **81,965** | **82.9M** | **26.9M** | **8,326.5M** | **$5,146.15** | **$26,352.91** | **$12,093.42** |

_8,682.3M total tokens processed. 95.9% cache hit rate._

_$38,446.33 total saved ($26,352.91 caching + $12,093.42 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 120,580 | 129K | 43.6M | 10,064.5M | $4,872.48 | $27,174.16 | $14,698.84 |
| claude-opus-4-6 | 9,645 | 10K | 3.3M | 838.3M | $2,059.06 | $11,318.23 | $0.00 |
| gpt-5.6-sol | 12,569 | 60.2M | 2.7M | 996.4M | $949.07 | $2,690.40 | $2,080.97 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 3,349 | 15.8M | 691K | 165.5M | $99.23 | $446.92 | $429.81 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,250 | 16K | 824K | 235.6M | $30.03 | $169.69 | $393.48 |
| gpt-5.6-luna | 1,541 | 13.8M | 131K | 30.7M | $19.41 | $82.92 | $210.45 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **187,204** | **158.8M** | **59.3M** | **14,576.6M** | **$9,154.44** | **$47,716.53** | **$21,740.31** |

_15,184.7M total tokens processed. 96% cache hit rate._

_$69,456.84 total saved ($47,716.53 caching + $21,740.31 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-14 16:03 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
