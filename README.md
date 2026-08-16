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
| Worker sessions | 437 | 1,662 | 5,011 | 8,173 |

_Screen time from screen-time-history:daily-observations; collection status: ok, stale. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 45 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 55,594 | 61K | 20.7M | 6,531.8M | $3,119.11 | $17,636.08 | $9,084.53 |
| claude-opus-4-6 | 3,524 | 4K | 1.2M | 347.6M | $944.30 | $4,693.39 | $0.00 |
| gpt-5.6-sol | 7,113 | 37.5M | 1.6M | 626.2M | $598.04 | $1,690.88 | $1,301.74 |
| deepseek-v4-flash-free | 2,527 | 6.9M | 582K | 220.6M | $102.76 | $595.64 | $382.87 |
| gpt-5.6-terra | 3,341 | 16.4M | 701K | 159.5M | $99.92 | $430.72 | $431.43 |
| gpt-5.6-luna | 1,818 | 17.2M | 142K | 31.4M | $23.16 | $84.94 | $252.91 |
| claude-haiku-4-5 | 2,357 | 13K | 441K | 127.8M | $17.66 | $92.02 | $213.00 |
| **Total** | **76,274** | **78.2M** | **25.5M** | **8,045.1M** | **$4,904.95** | **$25,223.66** | **$11,666.47** |

_8,398.4M total tokens processed. 95.8% cache hit rate._

_$36,890.13 total saved ($25,223.66 caching + $11,666.47 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 125,596 | 135K | 45.7M | 10,644.1M | $5,145.87 | $28,739.07 | $15,517.70 |
| claude-opus-4-6 | 9,813 | 10K | 3.3M | 854.6M | $2,095.91 | $11,537.69 | $0.00 |
| gpt-5.6-sol | 12,569 | 60.2M | 2.7M | 996.4M | $949.07 | $2,690.40 | $2,080.97 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 3,530 | 17.2M | 736K | 168.5M | $104.82 | $454.99 | $453.56 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,251 | 16K | 825K | 235.6M | $30.05 | $169.69 | $393.51 |
| gpt-5.6-luna | 1,818 | 17.2M | 142K | 31.4M | $23.16 | $84.94 | $252.91 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **192,847** | **163.7M** | **61.5M** | **15,176.2M** | **$9,474.04** | **$49,511.00** | **$22,625.41** |

_15,810.1M total tokens processed. 96% cache hit rate._

_$72,136.41 total saved ($49,511.00 caching + $22,625.41 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-16 17:27 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
