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
| Worker sessions | 456 | 1,548 | 4,889 | 7,944 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 44 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 58,119 | 63K | 21.4M | 6,686.0M | $3,164.09 | $18,052.34 | $9,310.58 |
| claude-opus-4-6 | 3,941 | 4K | 1.3M | 369.3M | $1,007.67 | $4,985.75 | $0.00 |
| gpt-5.6-sol | 7,113 | 37.5M | 1.6M | 626.2M | $598.04 | $1,690.88 | $1,301.74 |
| deepseek-v4-flash-free | 3,773 | 8.9M | 803K | 337.9M | $150.80 | $912.59 | $561.60 |
| gpt-5.6-terra | 3,329 | 16.4M | 699K | 159.4M | $99.61 | $430.39 | $430.12 |
| gpt-5.6-luna | 1,698 | 15.7M | 137K | 31.1M | $21.54 | $84.04 | $234.51 |
| claude-haiku-4-5 | 2,438 | 13K | 452K | 130.6M | $18.02 | $94.05 | $217.84 |
| **Total** | **80,411** | **78.7M** | **26.5M** | **8,340.7M** | **$5,059.77** | **$26,250.05** | **$12,056.39** |

_8,693.5M total tokens processed. 95.9% cache hit rate._

_$38,306.44 total saved ($26,250.05 caching + $12,056.39 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 123,475 | 132K | 44.7M | 10,465.5M | $5,034.46 | $28,257.03 | $15,242.72 |
| claude-opus-4-6 | 9,707 | 10K | 3.3M | 842.8M | $2,072.62 | $11,378.81 | $0.00 |
| gpt-5.6-sol | 12,569 | 60.2M | 2.7M | 996.4M | $949.07 | $2,690.40 | $2,080.97 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 3,518 | 17.1M | 734K | 168.3M | $104.51 | $454.67 | $452.25 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,251 | 16K | 825K | 235.6M | $30.05 | $169.69 | $393.51 |
| gpt-5.6-luna | 1,698 | 15.7M | 137K | 31.1M | $21.54 | $84.04 | $234.51 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **190,488** | **162.1M** | **60.4M** | **14,985.4M** | **$9,337.41** | **$48,868.86** | **$22,330.72** |

_15,605.2M total tokens processed. 96% cache hit rate._

_$71,199.58 total saved ($48,868.86 caching + $22,330.72 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-15 21:27 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
