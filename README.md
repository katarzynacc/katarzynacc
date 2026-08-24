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
| Screen time (Linux) | 23.9h | 131.1h | 490.8h | ~7323h* |
| Interactive human attention | 3.3h | 11.2h | 66.4h | 70.6h |
| Interactive AI generation | 6.4h | 35.1h | 187.5h | 194.3h |
| Worker-classified human attention | 0.0h | 2.5h | 8.8h | 8.8h |
| Worker/headless AI generation | 0.6h | 31.5h | 255.5h | 960.4h |
| Additive observed work | 10.2h | 79.5h | 516.4h | 1,232.3h |
| Interactive sessions | 6 | 23 | 88 | 93 |
| Worker sessions | 110 | 1,187 | 5,173 | 9,388 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 53 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 45,988 | 50K | 17.0M | 6,233.1M | $2,948.09 | $16,829.39 | $8,506.10 |
| claude-opus-4-6 | 2,735 | 2K | 962K | 284.9M | $656.90 | $3,847.36 | $0.00 |
| gpt-5.6-sol | 6,010 | 29.9M | 1.3M | 539.9M | $496.17 | $1,457.87 | $1,087.22 |
| gpt-5.6-terra | 3,869 | 19.5M | 862K | 185.1M | $94.51 | $499.77 | $508.45 |
| deepseek-v4-flash-free | 1,533 | 4.7M | 360K | 132.8M | $63.68 | $358.72 | $237.67 |
| claude-haiku-4-5 | 2,825 | 15K | 546K | 159.3M | $21.25 | $114.70 | $265.23 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 2,659 | 26.7M | 183K | 37.3M | $6.88 | $100.82 | $376.98 |
| x-preview-f-free | 203 | 308K | 55K | 14.7M | $6.44 | $39.74 | $24.71 |
| **Total** | **66,188** | **83.0M** | **21.4M** | **7,626.8M** | **$4,309.77** | **$23,355.09** | **$11,079.53** |

_7,965.2M total tokens processed. 95.8% cache hit rate._

_$34,434.62 total saved ($23,355.09 caching + $11,079.53 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 135,559 | 146K | 49.4M | 12,111.4M | $5,838.38 | $32,700.92 | $17,502.86 |
| claude-opus-4-6 | 10,486 | 11K | 3.5M | 930.7M | $2,277.89 | $12,565.28 | $0.00 |
| gpt-5.6-sol | 13,075 | 62.5M | 2.8M | 1,059.9M | $1,001.75 | $2,861.87 | $2,191.77 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 4,141 | 20.5M | 904K | 196.2M | $99.36 | $529.82 | $535.79 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,859 | 20K | 955K | 273.4M | $34.43 | $196.89 | $456.42 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 2,659 | 26.7M | 183K | 37.3M | $6.88 | $100.82 | $376.98 |
| x-preview-f-free | 203 | 308K | 55K | 14.7M | $6.44 | $39.74 | $24.71 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **206,618** | **180.8M** | **66.0M** | **16,908.8M** | **$10,406.14** | **$54,936.29** | **$25,088.46** |

_17,620.3M total tokens processed. 96% cache hit rate._

_$80,024.75 total saved ($54,936.29 caching + $25,088.46 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-24 14:21 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
