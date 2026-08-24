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
| Screen time (Linux) | 12.3h | 131.1h | 479.1h | ~7323h* |
| Interactive human attention | 3.3h | 11.2h | 66.4h | 70.6h |
| Interactive AI generation | 6.4h | 35.1h | 187.5h | 194.3h |
| Worker-classified human attention | 0.0h | 2.5h | 8.8h | 8.8h |
| Worker/headless AI generation | 0.6h | 31.5h | 255.5h | 960.4h |
| Additive observed work | 10.2h | 79.5h | 516.4h | 1,232.3h |
| Interactive sessions | 7 | 24 | 89 | 94 |
| Worker sessions | 205 | 1,279 | 5,265 | 9,480 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 53 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 47,878 | 52K | 17.8M | 6,378.4M | $3,003.38 | $17,221.91 | $8,723.64 |
| claude-opus-4-6 | 2,994 | 3K | 1.0M | 306.8M | $704.33 | $4,143.06 | $0.00 |
| gpt-5.6-sol | 5,959 | 29.6M | 1.3M | 537.8M | $493.21 | $1,452.23 | $1,080.54 |
| gpt-5.6-terra | 3,864 | 19.5M | 861K | 185.0M | $94.44 | $499.52 | $508.01 |
| deepseek-v4-flash-free | 1,481 | 4.5M | 341K | 129.5M | $61.76 | $349.69 | $230.37 |
| claude-haiku-4-5 | 2,825 | 15K | 546K | 159.3M | $21.25 | $114.70 | $265.23 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| x-preview-f-free | 272 | 415K | 87K | 19.9M | $8.99 | $53.82 | $34.15 |
| gpt-5.6-luna | 2,668 | 26.7M | 183K | 37.3M | $6.88 | $100.82 | $376.98 |
| **Total** | **68,307** | **82.6M** | **22.3M** | **7,793.8M** | **$4,410.09** | **$24,042.46** | **$11,292.10** |

_8,133.2M total tokens processed. 95.8% cache hit rate._

_$35,334.56 total saved ($24,042.46 caching + $11,292.10 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 137,724 | 148K | 50.2M | 12,308.9M | $5,926.29 | $33,234.04 | $17,787.24 |
| claude-opus-4-6 | 10,746 | 11K | 3.6M | 952.6M | $2,325.57 | $12,860.97 | $0.00 |
| gpt-5.6-sol | 13,075 | 62.5M | 2.8M | 1,059.9M | $1,001.75 | $2,861.87 | $2,191.77 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 4,144 | 20.5M | 904K | 196.2M | $99.36 | $529.82 | $535.79 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,859 | 20K | 955K | 273.4M | $34.43 | $196.89 | $456.42 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| x-preview-f-free | 272 | 415K | 87K | 19.9M | $8.99 | $53.82 | $34.15 |
| gpt-5.6-luna | 2,668 | 26.7M | 183K | 37.3M | $6.88 | $100.82 | $376.98 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **209,124** | **180.9M** | **66.9M** | **17,133.3M** | **$10,544.28** | **$55,779.18** | **$25,382.29** |

_17,850.8M total tokens processed. 96% cache hit rate._

_$81,161.46 total saved ($55,779.18 caching + $25,382.29 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-24 21:05 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
