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
| Interactive sessions | 3 | 12 | 71 | 71 |
| Worker sessions | 448 | 1,673 | 5,022 | 8,184 |

_Screen time from screen-time-history:daily-observations; collection status: ok, stale. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 45 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 54,929 | 60K | 20.4M | 6,487.0M | $3,098.98 | $17,515.16 | $9,013.56 |
| claude-opus-4-6 | 3,401 | 3K | 1.1M | 337.2M | $919.88 | $4,552.77 | $0.00 |
| gpt-5.6-sol | 7,113 | 37.5M | 1.6M | 626.2M | $598.04 | $1,690.88 | $1,301.74 |
| deepseek-v4-flash-free | 2,527 | 6.9M | 582K | 220.6M | $102.76 | $595.64 | $382.87 |
| gpt-5.6-terra | 3,341 | 16.4M | 701K | 159.5M | $99.92 | $430.72 | $431.43 |
| gpt-5.6-luna | 1,826 | 17.3M | 142K | 31.4M | $23.28 | $84.97 | $254.22 |
| claude-haiku-4-5 | 2,326 | 13K | 435K | 126.5M | $17.48 | $91.15 | $210.84 |
| **Total** | **75,463** | **78.3M** | **25.1M** | **7,988.7M** | **$4,860.34** | **$24,961.29** | **$11,594.67** |

_8,340.8M total tokens processed. 95.8% cache hit rate._

_$36,555.95 total saved ($24,961.29 caching + $11,594.67 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 125,698 | 135K | 45.7M | 10,651.6M | $5,152.22 | $28,759.37 | $15,529.34 |
| claude-opus-4-6 | 9,813 | 10K | 3.3M | 854.6M | $2,095.91 | $11,537.69 | $0.00 |
| gpt-5.6-sol | 12,569 | 60.2M | 2.7M | 996.4M | $949.07 | $2,690.40 | $2,080.97 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 3,530 | 17.2M | 736K | 168.5M | $104.82 | $454.99 | $453.56 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,251 | 16K | 825K | 235.6M | $30.05 | $169.69 | $393.51 |
| gpt-5.6-luna | 1,826 | 17.3M | 142K | 31.4M | $23.28 | $84.97 | $254.22 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **192,957** | **163.8M** | **61.5M** | **15,183.7M** | **$9,480.51** | **$49,531.33** | **$22,638.36** |

_15,818.7M total tokens processed. 96% cache hit rate._

_$72,169.70 total saved ($49,531.33 caching + $22,638.36 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-16 19:27 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
