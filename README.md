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
| Screen time (Linux) | 22.9h | 149.1h | 593.5h | ~7516h* |
| Interactive human attention | 1.3h | 12.6h | 54.2h | 144.1h |
| Interactive AI generation | 0.8h | 13.8h | 74.5h | 304.8h |
| Worker-classified human attention | 0.0h | 4.4h | 17.9h | 45.1h |
| Worker/headless AI generation | 2.4h | 53.5h | 254.3h | 1354.7h |
| Additive observed work | 4.7h | 84.0h | 399.6h | 1,844.9h |
| Interactive sessions | 2 | 11 | 30 | 140 |
| Worker sessions | 81 | 601 | 3,483 | 14,741 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 90 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 56,258 | 60K | 13.9M | 7,153.8M | 176.6M | 97.6% | 1,202 | 302.0h |
| claude-opus-4-6 | 3,030 | 3K | 837K | 470.1M | 15.3M | 96.8% | 119 | 18.4h |
| gpt-5.6-terra | 3,016 | 18.5M | 591K | 316.5M | 0 | 94.5% | 150 | 20.6h |
| gpt-5.6-luna | 2,277 | 31.9M | 99K | 18.9M | 0 | 37.2% | 2,180 | 8.4h |
| gpt-5.6-sol-fast | 1,611 | 9.1M | 328K | 172.2M | 0 | 95.0% | 10 | 19.5h |
| claude-sonnet-5-5 | 336 | 738 | 90K | 22.0M | 2.0M | 91.3% | 27 | 2.1h |
| ling-3.0-flash-fin-free | 328 | 3.1M | 70K | 35.1M | 0 | 91.9% | 2 | 1.1h |
| nemotron-3-ultra-free | 171 | 3.3M | 14K | 15.3M | 0 | 82.0% | 1 | 1.2h |
| gpt-5.6-sol | 89 | 379K | 16K | 13.8M | 0 | 97.3% | 1 | 0.6h |
| gpt-6-astra | 1 | 7K | 505 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **67,117** | **66.6M** | **15.9M** | **8,218.1M** | **194.1M** | **96.9%** | **3,681** | **373.8h** |

_8,494.8M total tokens processed. 96.9% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 206,705 | 222K | 69.2M | 20,450.7M | 605.1M | 97.1% | 5,009 | 1,139.8h |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | 0 | 97.2% | 199 | 47.7h |
| claude-opus-4-6 | 14,948 | 16K | 4.9M | 1,537.0M | 51.3M | 96.8% | 580 | 84.2h |
| gpt-5.6-sol | 13,650 | 65.6M | 2.9M | 1,121.9M | 0 | 94.5% | 692 | 98.0h |
| claude-sonnet-4-5 | 10,580 | 52K | 2.9M | 499.3M | 33.2M | 93.8% | 339 | 35.9h |
| gpt-5.6-terra | 8,667 | 52.9M | 1.8M | 637.2M | 0 | 92.3% | 1,318 | 58.3h |
| gpt-5.6-luna | 5,843 | 63.0M | 339K | 67.9M | 0 | 51.9% | 5,187 | 22.7h |
| claude-haiku-4-5 | 4,892 | 20K | 960K | 275.1M | 8.7M | 96.9% | 137 | 18.7h |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | 0 | 93.5% | 275 | 52.1h |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | 0 | 93.8% | 201 | 31.3h |
| gpt-5.6-sol-fast | 2,319 | 12.9M | 498K | 252.3M | 0 | 95.1% | 14 | 25.6h |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | 0 | 96.9% | 7 | 12.3h |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | 0 | 95.2% | 27 | 3.9h |
| nemotron-3-ultra-free | 369 | 8.0M | 27K | 40.4M | 0 | 83.4% | 2 | 2.4h |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | 0 | 95.9% | 2 | 3.1h |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | 5.5M | 92.6% | 1 | 3.6h |
| claude-sonnet-5-5 | 336 | 738 | 90K | 22.0M | 2.0M | 91.3% | 27 | 2.1h |
| ling-3.0-flash-fin-free | 328 | 3.1M | 70K | 35.1M | 0 | 91.9% | 2 | 1.1h |
| north-mini-code-free | 28 | 915K | 284 | 0 | 0 | 0.0% | 2 | 0.0h |
| claude-sonnet-4 | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-6-astra | 1 | 7K | 505 | 0 | 0 | 0.0% | 1 | 0.0h |
| pool-account-management | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **295,291** | **282.1M** | **89.7M** | **26,967.5M** | **706.2M** | **96.5%** | **13,964** | **1,642.9h** |

_28,045.5M total tokens processed. 96.5% cache hit rate._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-09-30 01:19 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<!-- TOTAL-CONTRIBUTIONS-START -->
<div align="center">
  <a href="https://commit-history.com/katarzynacc?metric=total" target="_blank" rel="noopener noreferrer">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/contributions/total-dark.svg" />
      <img alt="katarzynacc's cumulative total GitHub contributions" src="assets/contributions/total-light.svg" width="960" />
    </picture>
  </a>
</div>

[Verify on commit-history.com](https://commit-history.com/katarzynacc?metric=total) · [Chart data](assets/contributions/total.json)

Includes commits, issues, pull requests, reviews, repositories, and restricted contributions. Refreshed daily through the prior UTC day; commit-history.com may use a different refresh cutoff. GitHub controls link navigation—Ctrl/Cmd-click opens verification in a new tab.
<!-- TOTAL-CONTRIBUTIONS-END -->
