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
| Screen time (Linux) | 23.9h | 167.7h | 648.7h | ~7420h* |
| Interactive human attention | 0.1h | 10.9h | 37.8h | 37.8h |
| Interactive AI generation | 4.3h | 42.4h | 82.5h | 82.5h |
| Worker-classified human attention | 0.0h | 2.3h | 4.9h | 4.9h |
| Worker/headless AI generation | 9.1h | 91.4h | 450.2h | 861.8h |
| Additive observed work | 13.4h | 146.8h | 574.5h | 986.1h |
| Interactive sessions | 2 | 23 | 61 | 61 |
| Worker sessions | 294 | 1,143 | 4,389 | 6,690 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 38 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 85,999 | 92K | 31.2M | 7,531.7M | $3,572.20 | $20,335.66 | $10,911.81 |
| claude-opus-4-6 | 7,371 | 8K | 2.4M | 681.3M | $1,658.66 | $9,198.00 | $0.00 |
| gpt-5.6-sol | 12,281 | 58.7M | 2.6M | 971.4M | $924.61 | $2,623.05 | $2,029.58 |
| deepseek-v4-flash-free | 8,242 | 17.4M | 1.6M | 710.9M | $311.67 | $1,919.68 | $1,161.52 |
| claude-sonnet-4-5 | 1,098 | 14K | 355K | 77.7M | $56.35 | $209.88 | $114.78 |
| gpt-5.6-terra | 2,093 | 9.2M | 359K | 84.1M | $53.49 | $227.19 | $233.14 |
| gpt-5.4 | 764 | 3.1M | 242K | 70.0M | $30.56 | $131.42 | $116.64 |
| claude-haiku-4-5 | 2,501 | 14K | 473K | 137.7M | $18.69 | $99.19 | $229.47 |
| gpt-5.6-luna | 839 | 6.4M | 71K | 23.1M | $10.06 | $62.60 | $109.62 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 24 | 20K | 3K | 1.1M | $0.06 | $2.18 | $1.47 |
| **Total** | **121,240** | **96.0M** | **39.4M** | **10,289.6M** | **$6,639.17** | **$34,808.84** | **$14,919.02** |

_10,687.6M total tokens processed. 96.3% cache hit rate._

_$49,727.86 total saved ($34,808.84 caching + $14,919.02 model routing vs all-Opus)._

_Model savings are modest because ~96.3% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 114,940 | 123K | 41.6M | 8,910.8M | $4,311.18 | $24,059.21 | $13,190.92 |
| claude-opus-4-6 | 9,385 | 10K | 3.2M | 816.7M | $2,009.78 | $11,025.48 | $0.00 |
| gpt-5.6-sol | 12,281 | 58.7M | 2.6M | 971.4M | $924.61 | $2,623.05 | $2,029.58 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| gpt-5.6-terra | 2,093 | 9.2M | 359K | 84.1M | $53.49 | $227.19 | $233.14 |
| claude-haiku-4-5 | 4,134 | 16K | 799K | 229.4M | $29.22 | $165.22 | $382.89 |
| gpt-5.6-luna | 839 | 6.4M | 71K | 23.1M | $10.06 | $62.60 | $109.62 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **178,942** | **143.4M** | **56.7M** | **13,281.1M** | **$8,463.50** | **$43,996.97** | **$19,872.90** |

_13,821.3M total tokens processed. 96.1% cache hit rate._

_$63,869.87 total saved ($43,996.97 caching + $19,872.90 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-09 18:02 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
