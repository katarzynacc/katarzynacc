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
| Screen time (Linux) | 0h | 77.9h | 581.3h | ~7498h* |
| Interactive human attention | 2.4h | 19.0h | 59.4h | 59.4h |
| Interactive AI generation | 20.5h | 60.1h | 159.2h | 159.2h |
| Worker-classified human attention | 0.5h | 1.1h | 6.3h | 6.3h |
| Worker/headless AI generation | 8.9h | 54.1h | 287.1h | 928.8h |
| Additive observed work | 32.3h | 134.3h | 511.2h | 1,152.9h |
| Interactive sessions | 13 | 22 | 82 | 82 |
| Worker sessions | 427 | 1,631 | 5,105 | 8,373 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok, stale. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 46 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 53,536 | 59K | 19.9M | 6,505.2M | $3,099.77 | $17,564.27 | $9,002.14 |
| claude-opus-4-6 | 2,949 | 3K | 987K | 297.6M | $834.29 | $4,018.24 | $0.00 |
| gpt-5.6-sol | 7,163 | 38.1M | 1.6M | 654.1M | $618.76 | $1,766.25 | $1,341.68 |
| gpt-5.6-terra | 3,356 | 16.6M | 702K | 158.3M | $100.18 | $427.42 | $432.28 |
| deepseek-v4-flash-free | 2,096 | 6.2M | 507K | 180.0M | $86.28 | $486.03 | $321.16 |
| gpt-5.6-luna | 1,979 | 19.2M | 157K | 34.6M | $25.85 | $93.46 | $282.28 |
| claude-haiku-4-5 | 2,242 | 12K | 420K | 122.1M | $16.99 | $87.98 | $203.58 |
| **Total** | **73,321** | **80.4M** | **24.3M** | **7,952.2M** | **$4,782.12** | **$24,443.67** | **$11,583.12** |

_8,305.7M total tokens processed. 95.7% cache hit rate._

_$36,026.79 total saved ($24,443.67 caching + $11,583.12 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 127,307 | 137K | 46.3M | 10,955.5M | $5,288.84 | $29,580.12 | $15,931.34 |
| claude-opus-4-6 | 9,848 | 10K | 3.3M | 859.3M | $2,107.42 | $11,601.38 | $0.00 |
| gpt-5.6-sol | 13,074 | 62.5M | 2.8M | 1,059.9M | $1,001.70 | $2,861.87 | $2,191.64 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 3,578 | 17.5M | 744K | 169.2M | $105.99 | $457.00 | $458.48 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,251 | 16K | 825K | 235.6M | $30.05 | $169.69 | $393.51 |
| gpt-5.6-luna | 1,979 | 19.2M | 157K | 34.6M | $25.85 | $93.46 | $282.28 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **195,307** | **168.3M** | **62.3M** | **15,559.8M** | **$9,685.01** | **$50,597.74** | **$23,184.01** |

_16,210.0M total tokens processed. 96% cache hit rate._

_$73,781.75 total saved ($50,597.74 caching + $23,184.01 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-17 19:11 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
