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
| Worker sessions | 254 | 1,151 | 5,164 | 9,558 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 54 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 50,177 | 55K | 18.6M | 6,543.8M | $3,082.50 | $17,668.40 | $8,970.37 |
| claude-opus-4-6 | 3,097 | 3K | 1.0M | 323.6M | $736.47 | $4,369.75 | $0.00 |
| gpt-5.6-sol | 5,866 | 29.0M | 1.2M | 527.4M | $483.96 | $1,424.00 | $1,059.56 |
| gpt-5.6-terra | 3,843 | 19.4M | 861K | 184.7M | $94.21 | $498.82 | $506.66 |
| deepseek-v4-flash-free | 1,412 | 4.3M | 332K | 126.0M | $60.02 | $340.43 | $223.83 |
| claude-haiku-4-5 | 2,825 | 15K | 546K | 159.3M | $21.25 | $114.70 | $265.23 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| x-preview-f-free | 272 | 415K | 87K | 19.9M | $8.99 | $53.82 | $34.15 |
| gpt-5.6-luna | 2,685 | 26.7M | 183K | 37.3M | $6.88 | $100.82 | $376.98 |
| **Total** | **70,543** | **81.8M** | **23.1M** | **7,961.8M** | **$4,510.13** | **$24,677.46** | **$11,509.95** |

_8,306.1M total tokens processed. 95.9% cache hit rate._

_$36,187.41 total saved ($24,677.46 caching + $11,509.95 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 140,023 | 150K | 51.0M | 12,474.2M | $6,005.39 | $33,680.42 | $18,033.92 |
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
| gpt-5.6-luna | 2,685 | 26.7M | 183K | 37.3M | $6.88 | $100.82 | $376.98 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **211,545** | **180.9M** | **67.8M** | **17,315.4M** | **$10,655.52** | **$56,452.26** | **$25,628.96** |

_18,038.7M total tokens processed. 96% cache hit rate._

_$82,081.22 total saved ($56,452.26 caching + $25,628.96 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-25 01:29 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
