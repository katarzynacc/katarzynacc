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
| Screen time (Linux) | 24h | 59.7h | 563h | ~7319h* |
| Interactive human attention | 3.4h | 25.4h | 66.7h | 66.7h |
| Interactive AI generation | 11.8h | 80.5h | 185.2h | 185.2h |
| Worker-classified human attention | 1.8h | 3.5h | 8.8h | 8.8h |
| Worker/headless AI generation | 6.3h | 55.9h | 273.9h | 938.3h |
| Additive observed work | 22.7h | 164.4h | 532.8h | 1,197.1h |
| Interactive sessions | 3 | 25 | 85 | 85 |
| Worker sessions | 217 | 1,556 | 5,075 | 8,624 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 48 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 51,638 | 57K | 19.0M | 6,581.8M | $3,175.97 | $17,770.86 | $9,042.87 |
| claude-opus-4-6 | 3,022 | 3K | 1.0M | 312.3M | $791.55 | $4,216.85 | $0.00 |
| gpt-5.6-sol | 7,161 | 38.1M | 1.6M | 654.1M | $618.76 | $1,766.25 | $1,341.68 |
| gpt-5.6-terra | 3,518 | 17.6M | 747K | 164.7M | $105.44 | $444.77 | $454.16 |
| deepseek-v4-flash-free | 1,533 | 4.7M | 360K | 132.8M | $63.68 | $358.72 | $237.67 |
| gpt-5.6-luna | 2,154 | 21.1M | 164K | 35.3M | $27.98 | $95.55 | $305.88 |
| claude-haiku-4-5 | 2,661 | 14K | 514K | 148.9M | $20.03 | $107.27 | $248.31 |
| **Total** | **71,687** | **81.7M** | **23.5M** | **8,030.2M** | **$4,803.41** | **$24,760.27** | **$11,630.57** |

_8,398.8M total tokens processed. 95.6% cache hit rate._

_$36,390.84 total saved ($24,760.27 caching + $11,630.57 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 129,619 | 139K | 47.2M | 11,398.2M | $5,539.40 | $30,775.20 | $16,513.89 |
| claude-opus-4-6 | 10,027 | 10K | 3.4M | 880.3M | $2,155.23 | $11,885.37 | $0.00 |
| gpt-5.6-sol | 13,074 | 62.5M | 2.8M | 1,059.9M | $1,001.70 | $2,861.87 | $2,191.64 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 3,740 | 18.5M | 788K | 175.6M | $111.26 | $474.35 | $480.36 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,671 | 19K | 919K | 262.4M | $33.10 | $188.98 | $438.24 |
| gpt-5.6-luna | 2,154 | 21.1M | 164K | 35.3M | $27.98 | $95.55 | $305.88 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **198,555** | **171.1M** | **63.3M** | **16,057.4M** | **$9,993.83** | **$52,115.54** | **$23,856.78** |

_16,740.7M total tokens processed. 95.9% cache hit rate._

_$75,972.32 total saved ($52,115.54 caching + $23,856.78 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-18 23:12 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
