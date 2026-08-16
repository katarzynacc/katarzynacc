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
| Worker sessions | 424 | 1,649 | 4,998 | 8,160 |

_Screen time from screen-time-history:daily-observations; collection status: ok, stale. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 45 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 56,450 | 62K | 21.0M | 6,600.5M | $3,148.51 | $17,821.38 | $9,186.56 |
| claude-opus-4-6 | 3,682 | 4K | 1.2M | 360.2M | $977.53 | $4,863.83 | $0.00 |
| gpt-5.6-sol | 7,113 | 37.5M | 1.6M | 626.2M | $598.04 | $1,690.88 | $1,301.74 |
| deepseek-v4-flash-free | 2,527 | 6.9M | 582K | 220.6M | $102.76 | $595.64 | $382.87 |
| gpt-5.6-terra | 3,338 | 16.4M | 701K | 159.5M | $99.87 | $430.67 | $431.22 |
| gpt-5.6-luna | 1,810 | 17.1M | 141K | 31.4M | $23.05 | $84.90 | $251.59 |
| claude-haiku-4-5 | 2,357 | 13K | 441K | 127.8M | $17.66 | $92.02 | $213.00 |
| **Total** | **77,277** | **78.1M** | **25.9M** | **8,126.4M** | **$4,967.42** | **$25,579.32** | **$11,766.98** |

_8,481.4M total tokens processed. 95.8% cache hit rate._

_$37,346.30 total saved ($25,579.32 caching + $11,766.98 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 125,422 | 134K | 45.6M | 10,633.0M | $5,135.67 | $28,709.37 | $15,498.58 |
| claude-opus-4-6 | 9,813 | 10K | 3.3M | 854.6M | $2,095.91 | $11,537.69 | $0.00 |
| gpt-5.6-sol | 12,569 | 60.2M | 2.7M | 996.4M | $949.07 | $2,690.40 | $2,080.97 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 3,527 | 17.2M | 735K | 168.4M | $104.77 | $454.95 | $453.35 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,251 | 16K | 825K | 235.6M | $30.05 | $169.69 | $393.51 |
| gpt-5.6-luna | 1,810 | 17.1M | 141K | 31.4M | $23.05 | $84.90 | $251.59 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **192,662** | **163.5M** | **61.4M** | **15,165.1M** | **$9,463.68** | **$49,481.21** | **$22,604.76** |

_15,797.4M total tokens processed. 96% cache hit rate._

_$72,085.97 total saved ($49,481.21 caching + $22,604.76 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-16 16:26 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
