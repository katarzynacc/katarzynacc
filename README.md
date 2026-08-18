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
| Worker sessions | 375 | 1,689 | 5,204 | 8,576 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 47 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 53,844 | 59K | 20.0M | 6,680.2M | $3,228.98 | $18,036.81 | $9,218.08 |
| claude-opus-4-6 | 2,976 | 3K | 1.0M | 308.8M | $784.22 | $4,169.51 | $0.00 |
| gpt-5.6-sol | 7,161 | 38.1M | 1.6M | 654.1M | $618.76 | $1,766.25 | $1,341.68 |
| gpt-5.6-terra | 3,518 | 17.6M | 747K | 164.7M | $105.44 | $444.77 | $454.16 |
| deepseek-v4-flash-free | 1,533 | 4.7M | 360K | 132.8M | $63.68 | $358.72 | $237.67 |
| gpt-5.6-luna | 2,115 | 20.7M | 162K | 35.1M | $27.55 | $94.96 | $301.16 |
| claude-haiku-4-5 | 2,483 | 13K | 471K | 137.3M | $18.74 | $98.92 | $228.74 |
| **Total** | **73,630** | **81.3M** | **24.3M** | **8,113.4M** | **$4,847.37** | **$24,969.93** | **$11,781.48** |

_8,484.7M total tokens processed. 95.6% cache hit rate._

_$36,751.41 total saved ($24,969.93 caching + $11,781.48 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 129,227 | 139K | 47.1M | 11,317.2M | $5,504.85 | $30,556.47 | $16,408.46 |
| claude-opus-4-6 | 9,964 | 10K | 3.4M | 876.5M | $2,146.09 | $11,833.63 | $0.00 |
| gpt-5.6-sol | 13,074 | 62.5M | 2.8M | 1,059.9M | $1,001.70 | $2,861.87 | $2,191.64 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 3,740 | 18.5M | 788K | 175.6M | $111.26 | $474.35 | $480.36 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,493 | 18K | 875K | 250.8M | $31.81 | $180.63 | $418.67 |
| gpt-5.6-luna | 2,115 | 20.7M | 162K | 35.1M | $27.55 | $94.96 | $301.16 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **197,883** | **170.8M** | **63.1M** | **15,960.8M** | **$9,948.42** | **$51,836.13** | **$23,727.06** |

_16,640.9M total tokens processed. 95.9% cache hit rate._

_$75,563.19 total saved ($51,836.13 caching + $23,727.06 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-18 16:11 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
