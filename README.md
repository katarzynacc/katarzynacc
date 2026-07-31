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
| Screen time (Linux) | 23.9h | 167.8h | 493.2h | ~7286h* |
| Interactive human attention | 7.1h | 18.3h | 20.3h | 134.5h |
| Interactive AI generation | 9.4h | 31.9h | 32.6h | 114.5h |
| Worker-classified human attention | 0.0h | 0.2h | 0.6h | 25.0h |
| Worker/headless AI generation | 11.7h | 47.4h | 688.3h | 1058.9h |
| Additive observed work | 28.2h | 97.8h | 741.7h | 1,327.0h |
| Interactive sessions | 22 | 35 | 42 | 395 |
| Worker sessions | 425 | 1,496 | 4,900 | 9,054 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 64 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 97,897 | 104K | 35.2M | 6,881.9M | $3,350.18 | $18,581.35 | $10,375.37 |
| claude-opus-4-6 | 8,242 | 9K | 2.7M | 682.9M | $1,707.54 | $9,220.29 | $0.00 |
| gpt-5.6-sol | 9,699 | 45.9M | 2.0M | 742.8M | $715.91 | $2,005.61 | $1,567.55 |
| deepseek-v4-flash-free | 13,936 | 32.6M | 2.9M | 1,182.0M | $532.55 | $3,191.64 | $1,984.89 |
| claude-sonnet-4-5 | 7,509 | 18K | 1.8M | 299.7M | $162.53 | $809.37 | $469.31 |
| claude-sonnet-4-5 | 2,498 | 30K | 943K | 175.8M | $141.12 | $474.88 | $268.03 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,361 | 12.3M | 697K | 183.8M | $90.97 | $496.49 | $411.15 |
| claude-haiku-4-5 | 3,031 | 9K | 593K | 165.1M | $20.46 | $118.93 | $276.83 |
| gpt-5.6-terra | 1,048 | 3.6M | 82K | 24.1M | $17.04 | $65.15 | $78.09 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 692 | 1.6M | 102K | 35.4M | $1.92 | $66.48 | $58.45 |
| **Total** | **153,127** | **113.2M** | **48.3M** | **10,613.6M** | **$6,865.87** | **$35,479.20** | **$15,976.87** |

_11,038.9M total tokens processed. 96.1% cache hit rate._

_$51,456.07 total saved ($35,479.20 caching + $15,976.87 model routing vs all-Opus)._

_Model savings are modest because ~96.1% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 136,095 | 145K | 50.8M | 8,937.5M | $4,421.09 | $24,131.48 | $13,774.91 |
| claude-opus-4-6 | 8,579 | 9K | 2.9M | 712.1M | $1,782.23 | $9,614.30 | $0.00 |
| deepseek-v4-flash-free | 23,861 | 55.5M | 5.2M | 1,966.0M | $901.58 | $5,308.40 | $3,344.25 |
| gpt-5.6-sol | 9,699 | 45.9M | 2.0M | 742.8M | $715.91 | $2,005.61 | $1,567.55 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 25,384 | 45K | 5.5M | 1,322.5M | $162.38 | $952.20 | $2,269.78 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| gpt-5.6-terra | 1,048 | 3.6M | 82K | 24.1M | $17.04 | $65.15 | $78.09 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **262,964** | **176.3M** | **81.7M** | **16,865.1M** | **$10,412.41** | **$53,009.56** | **$26,115.83** |

_17,584.7M total tokens processed. 95.9% cache hit rate._

_$79,125.39 total saved ($53,009.56 caching + $26,115.83 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-31 16:03 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
