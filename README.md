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
| Input activity (Linux) | 0h | 4.2h | 9.4h | ~211h* |
| Interactive human attention | 0.0h | 1.4h | 6.9h | 165.7h |
| Interactive AI generation | 0.0h | 2.2h | 5.1h | 321.1h |
| Worker-classified human attention | 0.7h | 15.7h | 16.3h | 81.3h |
| Worker/headless AI generation | 2.0h | 17.3h | 41.0h | 1426.0h |
| Additive observed work | 2.7h | 36.7h | 69.4h | 1,988.8h |
| Interactive sessions | 10 | 15 | 23 | 199 |
| Worker sessions | 30 | 342 | 1,198 | 17,367 |

_Input activity from linux-input-activity:idle-cutoff-300s; collection status: ok. Input sampling began 2026-11-04 (16.3 of 28 days sampled); earlier days are not counted. Latest sample measured: desktop input. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 142 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-5-5 | 3,664 | 8K | 1.1M | 242.4M | 27.8M | 89.7% | 250 | 16.5h |
| gpt-5.6-terra | 2,033 | 11.1M | 430K | 161.4M | 0 | 93.5% | 151 | 11.9h |
| claude-opus-4-6 | 1,176 | 1K | 275K | 97.2M | 4.0M | 96.0% | 70 | 7.0h |
| gpt-5.6-sol | 1,047 | 5.2M | 150K | 68.2M | 0 | 92.9% | 122 | 5.4h |
| gpt-5.6-luna | 539 | 10.5M | 29K | 1.2M | 0 | 10.2% | 536 | 1.0h |
| deepseek-v4.1-flash-free | 513 | 1.4M | 129K | 52.4M | 0 | 97.3% | 6 | 2.6h |
| claude-sonnet-4-6 | 359 | 470 | 82K | 36.7M | 2.0M | 94.6% | 6 | 2.3h |
| deepseek-v4.1-flash | 340 | 743K | 67K | 35.5M | 0 | 97.9% | 7 | 1.0h |
| gpt-6-luna-fast | 71 | 602K | 18K | 8.4M | 0 | 93.3% | 2 | 0.4h |
| claude-haiku-5-5 | 7 | 28 | 13K | 35K | 653K | 5.2% | 6 | 0.0h |
| gpt-6-sol | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **9,750** | **29.7M** | **2.3M** | **703.7M** | **34.6M** | **91.6%** | **1,147** | **48.1h** |

_770.4M total tokens processed. 91.6% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 207,365 | 222K | 69.3M | 20,529.9M | 607.8M | 97.1% | 5,018 | 1,143.4h |
| claude-opus-4-6 | 17,946 | 19K | 5.5M | 1,789.7M | 61.6M | 96.7% | 810 | 101.6h |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | 0 | 97.2% | 199 | 47.7h |
| gpt-5.6-sol | 14,884 | 71.7M | 3.1M | 1,205.3M | 0 | 94.4% | 826 | 104.5h |
| gpt-5.6-terra | 11,978 | 72.8M | 2.5M | 914.3M | 0 | 92.6% | 1,540 | 77.3h |
| claude-sonnet-4-5 | 10,580 | 52K | 2.9M | 499.3M | 33.2M | 93.8% | 339 | 35.9h |
| gpt-5.6-luna | 7,312 | 87.4M | 427K | 80.9M | 0 | 48.1% | 6,517 | 26.2h |
| claude-sonnet-5-5 | 6,479 | 14K | 1.9M | 390.1M | 54.2M | 87.8% | 556 | 28.7h |
| claude-haiku-4-5 | 4,893 | 20K | 960K | 275.1M | 8.8M | 96.9% | 138 | 18.8h |
| gpt-5.5 | 4,643 | 13.3M | 741K | 190.8M | 0 | 93.5% | 276 | 52.1h |
| gpt-5.4 | 4,187 | 15.8M | 1.0M | 239.4M | 0 | 93.8% | 202 | 31.3h |
| gpt-5.6-sol-fast | 2,651 | 14.0M | 565K | 289.0M | 0 | 95.4% | 19 | 27.3h |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | 0 | 96.9% | 7 | 12.3h |
| nemotron-3-ultra-free | 977 | 23.6M | 95K | 102.5M | 0 | 81.3% | 7 | 5.5h |
| gpt-5.4-mini | 747 | 1.8M | 108K | 37.2M | 0 | 95.2% | 28 | 3.9h |
| deepseek-v4.1-flash-free | 513 | 1.4M | 129K | 52.4M | 0 | 97.3% | 6 | 2.6h |
| big-pickle | 474 | 2.1M | 90K | 39.0M | 0 | 94.8% | 4 | 2.4h |
| gpt-5.5-fast | 367 | 1.7M | 88K | 39.5M | 0 | 95.9% | 3 | 3.1h |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | 5.5M | 92.6% | 1 | 3.6h |
| deepseek-v4.1-flash | 340 | 743K | 67K | 35.5M | 0 | 97.9% | 7 | 1.0h |
| ling-3.0-flash-fin-free | 328 | 3.1M | 70K | 35.1M | 0 | 91.9% | 2 | 1.1h |
| gpt-6-luna-fast | 176 | 1.1M | 32K | 18.6M | 0 | 94.4% | 4 | 1.2h |
| north-mini-code-free | 28 | 915K | 284 | 0 | 0 | 0.0% | 2 | 0.0h |
| claude-haiku-5-5 | 7 | 28 | 13K | 35K | 653K | 5.2% | 6 | 0.0h |
| claude-sonnet-4 | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gemini-3.6-flash | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-5.4-fast | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-6-astra | 1 | 7K | 505 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-6-sol | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| pool-account-management | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **313,564** | **354.6M** | **93.8M** | **28,285.3M** | **772.0M** | **96.2%** | **16,432** | **1,731.5h** |

_29,505.9M total tokens processed. 96.2% cache hit rate._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-11-21 11:06 UTC by [aidevops](https://aidevops.sh) pulse._
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
