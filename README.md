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
| Screen time (Linux) | 24h | 167.8h | 670.9h | ~7498h* |
| Interactive human attention | 4.2h | 16.5h | 54.2h | 54.2h |
| Interactive AI generation | 6.2h | 58.4h | 136.7h | 136.7h |
| Worker-classified human attention | 0.0h | 0.9h | 5.8h | 5.8h |
| Worker/headless AI generation | 13.9h | 56.5h | 300.5h | 909.3h |
| Additive observed work | 24.3h | 132.4h | 496.3h | 1,105.1h |
| Interactive sessions | 4 | 11 | 70 | 70 |
| Worker sessions | 397 | 1,489 | 4,830 | 7,885 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 44 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 57,691 | 63K | 21.2M | 6,619.8M | $3,134.26 | $17,873.57 | $9,217.39 |
| claude-opus-4-6 | 4,038 | 4K | 1.4M | 374.7M | $1,020.51 | $5,059.56 | $0.00 |
| gpt-5.6-sol | 7,113 | 37.5M | 1.6M | 626.2M | $598.04 | $1,690.88 | $1,301.74 |
| deepseek-v4-flash-free | 4,195 | 9.6M | 880K | 379.1M | $167.40 | $1,023.73 | $623.07 |
| gpt-5.6-terra | 3,279 | 15.9M | 686K | 158.8M | $97.97 | $428.77 | $423.11 |
| gpt-5.6-luna | 1,674 | 15.4M | 136K | 31.0M | $21.23 | $83.78 | $231.16 |
| claude-haiku-4-5 | 2,438 | 13K | 452K | 130.6M | $18.02 | $94.05 | $217.84 |
| **Total** | **80,428** | **78.6M** | **26.4M** | **8,320.4M** | **$5,057.43** | **$26,254.34** | **$12,014.31** |

_8,671.4M total tokens processed. 96% cache hit rate._

_$38,268.65 total saved ($26,254.34 caching + $12,014.31 model routing vs all-Opus)._

_Model savings are modest because ~96% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 122,734 | 131K | 44.3M | 10,378.7M | $4,994.18 | $28,022.60 | $15,118.61 |
| claude-opus-4-6 | 9,648 | 10K | 3.3M | 838.4M | $2,059.69 | $11,318.41 | $0.00 |
| gpt-5.6-sol | 12,569 | 60.2M | 2.7M | 996.4M | $949.07 | $2,690.40 | $2,080.97 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 3,468 | 16.7M | 721K | 167.7M | $102.87 | $453.04 | $445.24 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,251 | 16K | 825K | 235.6M | $30.05 | $169.69 | $393.51 |
| gpt-5.6-luna | 1,674 | 15.4M | 136K | 31.0M | $21.23 | $83.78 | $231.16 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **189,614** | **161.4M** | **60.1M** | **14,893.4M** | **$9,282.25** | **$48,572.15** | **$22,196.26** |

_15,509.4M total tokens processed. 96% cache hit rate._

_$70,768.41 total saved ($48,572.15 caching + $22,196.26 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-15 17:23 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
