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
| Screen time (Linux) | 24h | 107.2h | 490.8h | ~7310h* |
| Interactive human attention | 0.0h | 10.3h | 63.8h | 67.3h |
| Interactive AI generation | 0.1h | 49.2h | 182.9h | 187.9h |
| Worker-classified human attention | 0.0h | 2.9h | 8.8h | 8.8h |
| Worker/headless AI generation | 11.0h | 39.9h | 257.9h | 959.8h |
| Additive observed work | 11.1h | 101.5h | 511.6h | 1,222.0h |
| Interactive sessions | 3 | 20 | 87 | 89 |
| Worker sessions | 217 | 1,361 | 5,299 | 9,306 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 52 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 45,738 | 50K | 16.8M | 6,096.3M | $2,910.05 | $16,460.18 | $8,330.01 |
| claude-opus-4-6 | 2,741 | 3K | 963K | 284.9M | $658.15 | $3,846.65 | $0.00 |
| gpt-5.6-sol | 6,010 | 29.9M | 1.3M | 539.9M | $496.17 | $1,457.87 | $1,087.22 |
| gpt-5.6-terra | 3,578 | 18.1M | 780K | 169.0M | $86.97 | $456.32 | $467.75 |
| deepseek-v4-flash-free | 1,533 | 4.7M | 360K | 132.8M | $63.68 | $358.72 | $237.67 |
| claude-haiku-4-5 | 2,818 | 15K | 543K | 159.2M | $21.14 | $114.66 | $264.92 |
| gpt-5.6-luna | 2,633 | 26.4M | 182K | 37.2M | $6.81 | $100.71 | $373.37 |
| **Total** | **65,051** | **79.3M** | **21.0M** | **7,419.6M** | **$4,242.97** | **$22,795.09** | **$10,760.93** |

_7,755.4M total tokens processed. 95.7% cache hit rate._

_$33,556.02 total saved ($22,795.09 caching + $10,760.93 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 134,226 | 144K | 48.9M | 11,885.2M | $5,748.60 | $32,090.22 | $17,198.69 |
| claude-opus-4-6 | 10,483 | 11K | 3.5M | 930.7M | $2,276.80 | $12,564.56 | $0.00 |
| gpt-5.6-sol | 13,075 | 62.5M | 2.8M | 1,059.9M | $1,001.75 | $2,861.87 | $2,191.77 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| gpt-5.6-terra | 3,850 | 19.1M | 822K | 180.1M | $91.82 | $486.37 | $495.09 |
| claude-haiku-4-5 | 4,852 | 20K | 951K | 273.4M | $34.32 | $196.86 | $456.11 |
| gpt-5.6-luna | 2,633 | 26.4M | 182K | 37.2M | $6.81 | $100.71 | $373.37 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **204,389** | **177.1M** | **65.3M** | **16,612.1M** | **$10,285.26** | **$54,134.79** | **$24,641.79** |

_17,315.4M total tokens processed. 95.9% cache hit rate._

_$78,776.59 total saved ($54,134.79 caching + $24,641.79 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-08-23 13:20 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
