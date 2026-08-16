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
| Worker sessions | 281 | 1,507 | 4,856 | 8,018 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 45 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 57,857 | 63K | 21.4M | 6,681.5M | $3,168.87 | $18,040.14 | $9,308.31 |
| claude-opus-4-6 | 3,781 | 4K | 1.3M | 363.6M | $988.65 | $4,909.41 | $0.00 |
| gpt-5.6-sol | 7,113 | 37.5M | 1.6M | 626.2M | $598.04 | $1,690.88 | $1,301.74 |
| deepseek-v4-flash-free | 3,521 | 8.4M | 761K | 313.2M | $140.41 | $845.66 | $522.78 |
| gpt-5.6-terra | 3,329 | 16.4M | 699K | 159.4M | $99.61 | $430.39 | $430.12 |
| gpt-5.6-luna | 1,730 | 16.1M | 138K | 31.2M | $21.98 | $84.27 | $239.48 |
| claude-haiku-4-5 | 2,357 | 13K | 441K | 127.8M | $17.66 | $92.02 | $213.00 |
| **Total** | **79,688** | **78.6M** | **26.5M** | **8,303.0M** | **$5,035.22** | **$26,092.77** | **$12,015.42** |

_8,656.6M total tokens processed. 95.9% cache hit rate._

_$38,108.18 total saved ($26,092.77 caching + $12,015.42 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 124,157 | 133K | 45.0M | 10,504.5M | $5,062.24 | $28,362.30 | $15,311.96 |
| claude-opus-4-6 | 9,762 | 10K | 3.3M | 850.7M | $2,086.24 | $11,485.21 | $0.00 |
| gpt-5.6-sol | 12,569 | 60.2M | 2.7M | 996.4M | $949.07 | $2,690.40 | $2,080.97 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 3,518 | 17.1M | 734K | 168.3M | $104.51 | $454.67 | $452.25 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,251 | 16K | 825K | 235.6M | $30.05 | $169.69 | $393.51 |
| gpt-5.6-luna | 1,730 | 16.1M | 138K | 31.2M | $21.98 | $84.27 | $239.48 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **191,257** | **162.5M** | **60.8M** | **15,032.4M** | **$9,379.25** | **$49,080.76** | **$22,404.93** |

_15,655.8M total tokens processed. 96% cache hit rate._

_$71,485.69 total saved ($49,080.76 caching + $22,404.93 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-16 03:27 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
