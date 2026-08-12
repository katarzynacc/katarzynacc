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
| Screen time (Linux) | 24h | 167.9h | 671.1h | ~7461h* |
| Interactive human attention | 0.9h | 5.1h | 41.3h | 41.3h |
| Interactive AI generation | 4.1h | 33.3h | 104.6h | 104.6h |
| Worker-classified human attention | 0.1h | 0.5h | 5.3h | 5.3h |
| Worker/headless AI generation | 7.1h | 52.5h | 335.8h | 882.4h |
| Additive observed work | 12.1h | 91.5h | 486.0h | 1,032.6h |
| Interactive sessions | 1 | 11 | 61 | 61 |
| Worker sessions | 231 | 940 | 4,431 | 7,118 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 41 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 68,077 | 73K | 24.7M | 6,639.6M | $3,132.86 | $17,927.08 | $9,454.98 |
| claude-opus-4-6 | 7,336 | 8K | 2.4M | 679.1M | $1,651.94 | $9,168.45 | $0.00 |
| gpt-5.6-sol | 10,361 | 51.3M | 2.3M | 858.5M | $819.12 | $2,318.07 | $1,784.82 |
| deepseek-v4-flash-free | 6,201 | 12.4M | 1.2M | 548.0M | $236.47 | $1,479.70 | $881.33 |
| gpt-5.6-terra | 2,578 | 11.8M | 508K | 121.8M | $73.77 | $328.99 | $318.85 |
| claude-sonnet-4-5 | 838 | 10K | 258K | 62.2M | $44.60 | $168.18 | $90.41 |
| claude-haiku-4-5 | 2,323 | 13K | 427K | 124.4M | $17.22 | $89.59 | $207.25 |
| gpt-5.6-luna | 1,078 | 8.4M | 85K | 25.3M | $12.49 | $68.32 | $136.82 |
| **Total** | **98,792** | **84.1M** | **32.0M** | **9,059.2M** | **$5,988.47** | **$31,548.37** | **$12,874.46** |

_9,416.0M total tokens processed. 96.2% cache hit rate._

_$44,422.83 total saved ($31,548.37 caching + $12,874.46 model routing vs all-Opus)._

_Model savings are modest because ~96.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 116,105 | 124K | 42.0M | 9,113.9M | $4,420.28 | $24,607.57 | $13,462.41 |
| claude-opus-4-6 | 9,385 | 10K | 3.2M | 816.7M | $2,009.78 | $11,025.48 | $0.00 |
| gpt-5.6-sol | 12,441 | 59.3M | 2.6M | 984.8M | $936.26 | $2,659.09 | $2,054.37 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| gpt-5.6-terra | 2,765 | 12.5M | 543K | 130.8M | $78.62 | $353.23 | $340.75 |
| claude-haiku-4-5 | 4,136 | 16K | 800K | 229.4M | $29.25 | $165.23 | $382.92 |
| gpt-5.6-luna | 1,078 | 8.4M | 85K | 25.3M | $12.49 | $68.32 | $136.82 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **181,180** | **149.3M** | **57.4M** | **13,546.4M** | **$8,611.84** | **$44,713.14** | **$20,304.03** |

_14,104.3M total tokens processed. 96% cache hit rate._

_$65,017.18 total saved ($44,713.14 caching + $20,304.03 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-12 02:02 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
