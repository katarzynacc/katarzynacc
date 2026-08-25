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
| Screen time (Linux) | 2.9h | 128.2h | 458h | ~7267h* |
| Interactive human attention | 3.0h | 10.3h | 67.9h | 73.6h |
| Interactive AI generation | 5.5h | 26.5h | 189.4h | 199.8h |
| Worker-classified human attention | 1.3h | 3.1h | 10.0h | 10.1h |
| Worker/headless AI generation | 21.6h | 50.1h | 273.7h | 982.0h |
| Additive observed work | 31.1h | 89.0h | 539.1h | 1,263.5h |
| Interactive sessions | 6 | 13 | 88 | 95 |
| Worker sessions | 412 | 1,309 | 5,322 | 9,716 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 54 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 53,250 | 58K | 19.8M | 6,798.3M | $3,210.61 | $18,355.67 | $9,351.49 |
| claude-opus-4-6 | 3,147 | 3K | 1.0M | 332.5M | $753.81 | $4,488.94 | $0.00 |
| gpt-5.6-sol | 5,759 | 28.3M | 1.2M | 521.4M | $476.58 | $1,407.87 | $1,042.52 |
| gpt-5.6-terra | 3,780 | 19.1M | 859K | 184.0M | $93.46 | $497.05 | $502.32 |
| deepseek-v4-flash-free | 1,412 | 4.3M | 332K | 126.0M | $60.02 | $340.43 | $223.83 |
| x-preview-f-free | 686 | 1.4M | 183K | 84.3M | $33.47 | $227.77 | $129.55 |
| claude-haiku-4-5 | 2,825 | 15K | 546K | 159.3M | $21.25 | $114.70 | $265.23 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 2,738 | 26.7M | 183K | 37.3M | $6.88 | $100.82 | $376.98 |
| **Total** | **73,963** | **81.8M** | **24.4M** | **8,283.0M** | **$4,671.93** | **$25,639.97** | **$11,965.09** |

_8,637.5M total tokens processed. 95.9% cache hit rate._

_$37,605.06 total saved ($25,639.97 caching + $11,965.09 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 143,096 | 154K | 52.3M | 12,728.7M | $6,133.51 | $34,367.70 | $18,415.03 |
| claude-opus-4-6 | 10,899 | 11K | 3.7M | 978.2M | $2,375.05 | $13,206.85 | $0.00 |
| gpt-5.6-sol | 13,075 | 62.5M | 2.8M | 1,059.9M | $1,001.75 | $2,861.87 | $2,191.77 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 4,146 | 20.5M | 904K | 196.2M | $99.36 | $529.82 | $535.79 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,859 | 20K | 955K | 273.4M | $34.43 | $196.89 | $456.42 |
| x-preview-f-free | 686 | 1.4M | 183K | 84.3M | $33.47 | $227.77 | $129.55 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 2,738 | 26.7M | 183K | 37.3M | $6.88 | $100.82 | $376.98 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **215,135** | **181.9M** | **69.1M** | **17,643.2M** | **$10,825.46** | **$57,432.67** | **$26,105.48** |

_18,377.8M total tokens processed. 96% cache hit rate._

_$83,538.15 total saved ($57,432.67 caching + $26,105.48 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-25 12:29 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
