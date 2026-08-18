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
| Screen time (Linux) | 5.8h | 59.7h | 563h | ~7306h* |
| Interactive human attention | 3.9h | 22.9h | 63.3h | 63.3h |
| Interactive AI generation | 14.1h | 72.8h | 173.3h | 173.3h |
| Worker-classified human attention | 0.7h | 1.8h | 7.0h | 7.0h |
| Worker/headless AI generation | 3.1h | 56.6h | 279.4h | 931.9h |
| Additive observed work | 21.6h | 153.9h | 521.9h | 1,174.5h |
| Interactive sessions | 13 | 23 | 83 | 83 |
| Worker sessions | 250 | 1,564 | 5,079 | 8,451 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 47 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 53,729 | 59K | 20.0M | 6,567.0M | $3,136.78 | $17,731.12 | $9,081.99 |
| claude-opus-4-6 | 3,000 | 3K | 1.0M | 307.9M | $854.68 | $4,156.77 | $0.00 |
| gpt-5.6-sol | 7,163 | 38.1M | 1.6M | 654.1M | $618.76 | $1,766.25 | $1,341.68 |
| gpt-5.6-terra | 3,473 | 17.3M | 735K | 162.5M | $103.88 | $438.83 | $447.68 |
| deepseek-v4-flash-free | 2,028 | 5.7M | 491K | 176.8M | $83.52 | $477.37 | $310.61 |
| gpt-5.6-luna | 2,019 | 19.6M | 159K | 34.7M | $26.33 | $93.95 | $287.65 |
| claude-haiku-4-5 | 2,242 | 12K | 420K | 122.1M | $16.99 | $87.98 | $203.58 |
| **Total** | **73,654** | **81.0M** | **24.4M** | **8,025.4M** | **$4,840.94** | **$24,752.27** | **$11,673.19** |

_8,384.4M total tokens processed. 95.7% cache hit rate._

_$36,425.46 total saved ($24,752.27 caching + $11,673.19 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 128,093 | 137K | 46.7M | 11,102.5M | $5,364.77 | $29,976.97 | $16,126.99 |
| claude-opus-4-6 | 9,902 | 10K | 3.4M | 869.6M | $2,128.60 | $11,739.91 | $0.00 |
| gpt-5.6-sol | 13,074 | 62.5M | 2.8M | 1,059.9M | $1,001.70 | $2,861.87 | $2,191.64 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 3,695 | 18.2M | 777K | 173.4M | $109.70 | $468.41 | $473.88 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,251 | 16K | 825K | 235.6M | $30.05 | $169.69 | $393.51 |
| gpt-5.6-luna | 2,019 | 19.6M | 159K | 34.7M | $26.33 | $93.95 | $287.65 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **196,304** | **169.4M** | **62.7M** | **15,721.4M** | **$9,786.31** | **$51,145.01** | **$23,400.44** |

_16,380.5M total tokens processed. 96% cache hit rate._

_$74,545.45 total saved ($51,145.01 caching + $23,400.44 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-18 01:11 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
