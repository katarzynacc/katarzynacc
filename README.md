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
| Screen time (Linux) | 0h | 143.9h | 647h | ~7498h* |
| Interactive human attention | 2.8h | 19.2h | 57.0h | 57.0h |
| Interactive AI generation | 2.0h | 56.2h | 138.7h | 138.7h |
| Worker-classified human attention | 0.0h | 0.9h | 5.8h | 5.8h |
| Worker/headless AI generation | 10.6h | 58.1h | 295.9h | 919.9h |
| Additive observed work | 15.5h | 134.4h | 496.5h | 1,120.5h |
| Interactive sessions | 2 | 11 | 70 | 70 |
| Worker sessions | 358 | 1,583 | 4,932 | 8,094 |

_Screen time from screen-time-history:daily-observations; collection status: ok, stale. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 45 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 57,039 | 62K | 21.2M | 6,650.0M | $3,159.09 | $17,955.05 | $9,256.42 |
| claude-opus-4-6 | 3,743 | 4K | 1.3M | 361.5M | $983.13 | $4,880.96 | $0.00 |
| gpt-5.6-sol | 7,113 | 37.5M | 1.6M | 626.2M | $598.04 | $1,690.88 | $1,301.74 |
| deepseek-v4-flash-free | 2,752 | 7.2M | 617K | 241.8M | $111.13 | $653.12 | $414.40 |
| gpt-5.6-terra | 3,338 | 16.4M | 701K | 159.5M | $99.87 | $430.67 | $431.22 |
| gpt-5.6-luna | 1,778 | 16.7M | 140K | 31.3M | $22.63 | $84.60 | $246.92 |
| claude-haiku-4-5 | 2,357 | 13K | 441K | 127.8M | $17.66 | $92.02 | $213.00 |
| **Total** | **78,120** | **78.1M** | **26.1M** | **8,198.3M** | **$4,991.55** | **$25,787.30** | **$11,863.71** |

_8,551.8M total tokens processed. 95.9% cache hit rate._

_$37,651.00 total saved ($25,787.30 caching + $11,863.71 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 124,787 | 134K | 45.3M | 10,568.2M | $5,095.12 | $28,534.29 | $15,403.68 |
| claude-opus-4-6 | 9,762 | 10K | 3.3M | 850.7M | $2,086.24 | $11,485.21 | $0.00 |
| gpt-5.6-sol | 12,569 | 60.2M | 2.7M | 996.4M | $949.07 | $2,690.40 | $2,080.97 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 3,527 | 17.2M | 735K | 168.4M | $104.77 | $454.95 | $453.35 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,251 | 16K | 825K | 235.6M | $30.05 | $169.69 | $393.51 |
| gpt-5.6-luna | 1,778 | 16.7M | 140K | 31.3M | $22.63 | $84.60 | $246.92 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **191,944** | **163.2M** | **61.1M** | **15,096.3M** | **$9,413.04** | **$49,253.36** | **$22,505.20** |

_15,723.3M total tokens processed. 96% cache hit rate._

_$71,758.56 total saved ($49,253.36 caching + $22,505.20 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-16 10:27 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
