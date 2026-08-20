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
| Screen time (Linux) | 0h | 5.9h | 509.3h | ~7333h* |
| Interactive human attention | 0.6h | 21.7h | 67.3h | 67.3h |
| Interactive AI generation | 2.4h | 69.1h | 187.6h | 187.6h |
| Worker-classified human attention | 0.0h | 2.9h | 8.8h | 8.8h |
| Worker/headless AI generation | 7.6h | 56.0h | 268.1h | 945.8h |
| Additive observed work | 10.6h | 148.9h | 529.9h | 1,207.7h |
| Interactive sessions | 2 | 24 | 86 | 86 |
| Worker sessions | 272 | 1,586 | 5,248 | 8,883 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 49 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 49,310 | 54K | 18.1M | 6,334.0M | $3,057.37 | $17,101.84 | $8,690.09 |
| claude-opus-4-6 | 2,906 | 3K | 1.0M | 293.4M | $690.48 | $3,962.17 | $0.00 |
| gpt-5.6-sol | 6,045 | 30.0M | 1.3M | 547.5M | $500.74 | $1,478.33 | $1,097.67 |
| gpt-5.6-terra | 3,470 | 17.5M | 746K | 164.5M | $105.23 | $444.34 | $453.16 |
| deepseek-v4-flash-free | 1,533 | 4.7M | 360K | 132.8M | $63.68 | $358.72 | $237.67 |
| gpt-5.6-luna | 2,333 | 23.0M | 171K | 36.1M | $30.18 | $97.72 | $329.94 |
| claude-haiku-4-5 | 2,783 | 15K | 535K | 157.0M | $20.87 | $113.08 | $261.27 |
| **Total** | **68,380** | **75.4M** | **22.3M** | **7,665.7M** | **$4,468.55** | **$23,556.20** | **$11,069.80** |

_8,014.8M total tokens processed. 95.6% cache hit rate._

_$34,626.00 total saved ($23,556.20 caching + $11,069.80 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 130,961 | 141K | 47.7M | 11,504.9M | $5,590.25 | $31,063.48 | $16,670.82 |
| claude-opus-4-6 | 10,317 | 11K | 3.5M | 911.5M | $2,227.57 | $12,306.24 | $0.00 |
| gpt-5.6-sol | 13,075 | 62.5M | 2.8M | 1,059.9M | $1,001.75 | $2,861.87 | $2,191.77 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 3,741 | 18.5M | 788K | 175.6M | $111.28 | $474.35 | $480.49 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,793 | 19K | 940K | 270.5M | $33.94 | $194.79 | $451.20 |
| gpt-5.6-luna | 2,333 | 23.0M | 171K | 36.1M | $30.18 | $97.72 | $329.94 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **200,490** | **173.0M** | **64.0M** | **16,204.3M** | **$10,120.13** | **$52,832.67** | **$24,050.98** |

_16,894.1M total tokens processed. 95.9% cache hit rate._

_$76,883.65 total saved ($52,832.67 caching + $24,050.98 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-20 20:32 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
