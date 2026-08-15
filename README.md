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
| Interactive sessions | 3 | 10 | 69 | 69 |
| Worker sessions | 321 | 1,413 | 4,754 | 7,809 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 44 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 57,179 | 62K | 21.0M | 6,585.6M | $3,118.84 | $17,781.15 | $9,167.14 |
| claude-opus-4-6 | 4,038 | 4K | 1.4M | 374.7M | $1,020.51 | $5,059.56 | $0.00 |
| gpt-5.6-sol | 7,113 | 37.5M | 1.6M | 626.2M | $598.04 | $1,690.88 | $1,301.74 |
| deepseek-v4-flash-free | 4,195 | 9.6M | 880K | 379.1M | $167.40 | $1,023.73 | $623.07 |
| gpt-5.6-terra | 3,245 | 15.7M | 678K | 158.1M | $97.16 | $426.92 | $419.63 |
| gpt-5.6-luna | 1,628 | 14.9M | 134K | 30.8M | $20.65 | $83.33 | $224.53 |
| claude-haiku-4-5 | 2,438 | 13K | 452K | 130.6M | $18.02 | $94.05 | $217.84 |
| **Total** | **79,836** | **77.9M** | **26.2M** | **8,285.4M** | **$5,040.62** | **$26,159.63** | **$11,953.95** |

_8,634.7M total tokens processed. 96% cache hit rate._

_$38,113.58 total saved ($26,159.63 caching + $11,953.95 model routing vs all-Opus)._

_Model savings are modest because ~96% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 122,072 | 131K | 44.1M | 10,327.4M | $4,970.18 | $27,884.03 | $15,042.13 |
| claude-opus-4-6 | 9,648 | 10K | 3.3M | 838.4M | $2,059.69 | $11,318.41 | $0.00 |
| gpt-5.6-sol | 12,569 | 60.2M | 2.7M | 996.4M | $949.07 | $2,690.40 | $2,080.97 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 3,434 | 16.5M | 713K | 167.1M | $102.06 | $451.20 | $441.76 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,251 | 16K | 825K | 235.6M | $30.05 | $169.69 | $393.51 |
| gpt-5.6-luna | 1,628 | 14.9M | 134K | 30.8M | $20.65 | $83.33 | $224.53 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **188,872** | **160.7M** | **59.8M** | **14,841.2M** | **$9,256.86** | **$48,431.29** | **$22,109.66** |

_15,455.0M total tokens processed. 96% cache hit rate._

_$70,540.95 total saved ($48,431.29 caching + $22,109.66 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-15 09:23 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
