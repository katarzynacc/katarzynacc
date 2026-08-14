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
| Screen time (Linux) | 23.9h | 167.8h | 671h | ~7486h* |
| Interactive human attention | 4.4h | 12.3h | 50.0h | 50.0h |
| Interactive AI generation | 12.0h | 52.2h | 130.5h | 130.5h |
| Worker-classified human attention | 0.0h | 0.9h | 5.8h | 5.8h |
| Worker/headless AI generation | 5.6h | 42.6h | 311.7h | 895.4h |
| Additive observed work | 22.0h | 108.1h | 497.0h | 1,080.8h |
| Interactive sessions | 5 | 8 | 67 | 67 |
| Worker sessions | 317 | 1,218 | 4,697 | 7,614 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 43 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 58,637 | 64K | 21.7M | 6,566.4M | $3,126.84 | $17,729.45 | $9,188.16 |
| claude-opus-4-6 | 4,303 | 4K | 1.5M | 412.9M | $1,094.56 | $5,574.78 | $0.00 |
| gpt-5.6-sol | 8,366 | 44.2M | 1.9M | 721.4M | $699.69 | $1,948.00 | $1,511.90 |
| deepseek-v4-flash-free | 4,915 | 10.4M | 1.0M | 444.3M | $192.99 | $1,199.88 | $718.51 |
| gpt-5.6-terra | 3,155 | 15.0M | 655K | 156.0M | $94.13 | $421.33 | $406.78 |
| gpt-5.6-luna | 1,510 | 13.3M | 130K | 30.6M | $18.96 | $82.77 | $205.37 |
| claude-haiku-4-5 | 2,323 | 13K | 427K | 124.4M | $17.22 | $89.59 | $207.25 |
| claude-sonnet-4-5 | 24 | 316 | 5K | 2.2M | $1.17 | $6.16 | $3.05 |
| **Total** | **83,233** | **83.1M** | **27.4M** | **8,458.7M** | **$5,245.56** | **$27,051.95** | **$12,241.04** |

_8,815.5M total tokens processed. 96% cache hit rate._

_$39,292.98 total saved ($27,051.95 caching + $12,241.04 model routing vs all-Opus)._

_Model savings are modest because ~96% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 119,832 | 128K | 43.4M | 10,012.3M | $4,845.21 | $27,033.39 | $14,620.92 |
| claude-opus-4-6 | 9,532 | 10K | 3.2M | 826.1M | $2,034.90 | $11,153.06 | $0.00 |
| gpt-5.6-sol | 12,569 | 60.2M | 2.7M | 996.4M | $949.07 | $2,690.40 | $2,080.97 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 3,344 | 15.7M | 690K | 165.0M | $99.03 | $445.61 | $428.91 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,136 | 16K | 800K | 229.4M | $29.25 | $165.23 | $382.92 |
| gpt-5.6-luna | 1,510 | 13.3M | 130K | 30.6M | $18.96 | $82.77 | $205.37 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **186,193** | **158.3M** | **59.0M** | **14,505.5M** | **$9,101.58** | **$47,404.67** | **$21,645.85** |

_15,110.5M total tokens processed. 96% cache hit rate._

_$69,050.52 total saved ($47,404.67 caching + $21,645.85 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-14 10:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
