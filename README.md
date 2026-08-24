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
| Interactive sessions | 3 | 20 | 85 | 90 |
| Worker sessions | 30 | 1,107 | 5,093 | 9,308 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 53 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 46,036 | 50K | 17.0M | 6,247.7M | $2,956.18 | $16,868.93 | $8,522.41 |
| claude-opus-4-6 | 2,732 | 2K | 961K | 284.9M | $655.82 | $3,846.65 | $0.00 |
| gpt-5.6-sol | 6,010 | 29.9M | 1.3M | 539.9M | $496.17 | $1,457.87 | $1,087.22 |
| gpt-5.6-terra | 3,586 | 18.2M | 780K | 169.0M | $87.09 | $456.52 | $468.33 |
| deepseek-v4-flash-free | 1,533 | 4.7M | 360K | 132.8M | $63.68 | $358.72 | $237.67 |
| claude-haiku-4-5 | 2,818 | 15K | 543K | 159.2M | $21.14 | $114.66 | $264.92 |
| gpt-5.6-luna | 2,633 | 26.4M | 182K | 37.2M | $6.81 | $100.71 | $373.37 |
| **Total** | **65,348** | **79.4M** | **21.2M** | **7,571.1M** | **$4,286.89** | **$23,204.04** | **$10,953.91** |

_7,906.4M total tokens processed. 95.8% cache hit rate._

_$34,157.96 total saved ($23,204.04 caching + $10,953.91 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 135,087 | 145K | 49.2M | 12,077.5M | $5,822.63 | $32,609.40 | $17,451.36 |
| claude-opus-4-6 | 10,483 | 11K | 3.5M | 930.7M | $2,276.80 | $12,564.56 | $0.00 |
| gpt-5.6-sol | 13,075 | 62.5M | 2.8M | 1,059.9M | $1,001.75 | $2,861.87 | $2,191.77 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| gpt-5.6-terra | 3,858 | 19.1M | 823K | 180.2M | $91.93 | $486.57 | $495.68 |
| claude-haiku-4-5 | 4,852 | 20K | 951K | 273.4M | $34.32 | $196.86 | $456.11 |
| gpt-5.6-luna | 2,633 | 26.4M | 182K | 37.2M | $6.81 | $100.71 | $373.37 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **205,258** | **177.1M** | **65.6M** | **16,804.4M** | **$10,359.40** | **$54,654.17** | **$24,895.04** |

_17,511.1M total tokens processed. 96% cache hit rate._

_$79,549.21 total saved ($54,654.17 caching + $24,895.04 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-24 03:20 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
