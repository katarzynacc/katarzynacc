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
| Screen time (Linux) | 5.8h | 59.7h | 563h | ~7306h* |
| Interactive human attention | 3.9h | 22.9h | 63.3h | 63.3h |
| Interactive AI generation | 14.1h | 72.8h | 173.3h | 173.3h |
| Worker-classified human attention | 0.7h | 1.8h | 7.0h | 7.0h |
| Worker/headless AI generation | 3.1h | 56.6h | 279.4h | 931.9h |
| Additive observed work | 21.6h | 153.9h | 521.9h | 1,174.5h |
| Interactive sessions | 15 | 25 | 85 | 85 |
| Worker sessions | 366 | 1,680 | 5,195 | 8,567 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 47 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 54,064 | 59K | 20.0M | 6,705.5M | $3,238.13 | $18,105.12 | $9,253.25 |
| claude-opus-4-6 | 2,956 | 3K | 995K | 303.3M | $784.07 | $4,095.07 | $0.00 |
| gpt-5.6-sol | 7,161 | 38.1M | 1.6M | 654.1M | $618.76 | $1,766.25 | $1,341.68 |
| gpt-5.6-terra | 3,518 | 17.6M | 747K | 164.7M | $105.44 | $444.77 | $454.16 |
| deepseek-v4-flash-free | 1,533 | 4.7M | 360K | 132.8M | $63.68 | $358.72 | $237.67 |
| gpt-5.6-luna | 2,107 | 20.6M | 162K | 35.1M | $27.45 | $94.88 | $300.00 |
| claude-haiku-4-5 | 2,483 | 13K | 471K | 137.3M | $18.74 | $98.92 | $228.74 |
| **Total** | **73,822** | **81.2M** | **24.4M** | **8,133.2M** | **$4,856.27** | **$24,963.72** | **$11,815.49** |

_8,505.0M total tokens processed. 95.6% cache hit rate._

_$36,779.21 total saved ($24,963.72 caching + $11,815.49 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 129,155 | 139K | 47.0M | 11,305.1M | $5,499.40 | $30,524.01 | $16,392.74 |
| claude-opus-4-6 | 9,941 | 10K | 3.4M | 871.0M | $2,132.43 | $11,759.19 | $0.00 |
| gpt-5.6-sol | 13,074 | 62.5M | 2.8M | 1,059.9M | $1,001.70 | $2,861.87 | $2,191.64 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 3,740 | 18.5M | 788K | 175.6M | $111.26 | $474.35 | $480.36 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,493 | 18K | 875K | 250.8M | $31.81 | $180.63 | $418.67 |
| gpt-5.6-luna | 2,107 | 20.6M | 162K | 35.1M | $27.45 | $94.88 | $300.00 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **197,780** | **170.7M** | **63.1M** | **15,943.2M** | **$9,929.21** | **$51,729.15** | **$23,710.17** |

_16,622.6M total tokens processed. 95.9% cache hit rate._

_$75,439.32 total saved ($51,729.15 caching + $23,710.17 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-18 15:11 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
