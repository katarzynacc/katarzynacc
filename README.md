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
| Interactive sessions | 5 | 12 | 87 | 94 |
| Worker sessions | 265 | 1,162 | 5,175 | 9,569 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 54 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 50,374 | 55K | 18.6M | 6,560.7M | $3,092.97 | $17,713.96 | $8,995.27 |
| claude-opus-4-6 | 3,097 | 3K | 1.0M | 323.6M | $736.47 | $4,369.75 | $0.00 |
| gpt-5.6-sol | 5,825 | 28.6M | 1.2M | 524.3M | $479.83 | $1,415.76 | $1,049.96 |
| gpt-5.6-terra | 3,835 | 19.4M | 860K | 184.6M | $94.13 | $498.57 | $506.22 |
| deepseek-v4-flash-free | 1,412 | 4.3M | 332K | 126.0M | $60.02 | $340.43 | $223.83 |
| claude-haiku-4-5 | 2,825 | 15K | 546K | 159.3M | $21.25 | $114.70 | $265.23 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| x-preview-f-free | 272 | 415K | 87K | 19.9M | $8.99 | $53.82 | $34.15 |
| gpt-5.6-luna | 2,693 | 26.7M | 183K | 37.3M | $6.88 | $100.82 | $376.98 |
| **Total** | **70,699** | **81.3M** | **23.1M** | **7,975.6M** | **$4,516.39** | **$24,714.53** | **$11,524.81** |

_8,320.5M total tokens processed. 95.9% cache hit rate._

_$36,239.34 total saved ($24,714.53 caching + $11,524.81 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 140,220 | 151K | 51.1M | 12,491.1M | $6,015.87 | $33,725.99 | $18,058.81 |
| claude-opus-4-6 | 10,849 | 11K | 3.7M | 969.4M | $2,357.71 | $13,087.67 | $0.00 |
| gpt-5.6-sol | 13,075 | 62.5M | 2.8M | 1,059.9M | $1,001.75 | $2,861.87 | $2,191.77 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 4,146 | 20.5M | 904K | 196.2M | $99.36 | $529.82 | $535.79 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,859 | 20K | 955K | 273.4M | $34.43 | $196.89 | $456.42 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| x-preview-f-free | 272 | 415K | 87K | 19.9M | $8.99 | $53.82 | $34.15 |
| gpt-5.6-luna | 2,693 | 26.7M | 183K | 37.3M | $6.88 | $100.82 | $376.98 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **211,750** | **180.9M** | **67.9M** | **17,332.3M** | **$10,666.00** | **$56,497.82** | **$25,653.86** |

_18,056.8M total tokens processed. 96% cache hit rate._

_$82,151.68 total saved ($56,497.82 caching + $25,653.86 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-25 02:29 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
