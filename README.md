# ccastle13

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
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
| Screen time (Linux) | 25h | 168.5h | 657.2h | ~7872h* |
| Interactive human attention | 3.2h | 25.6h | 153.1h | 517.5h |
| Interactive AI generation | 10.9h | 100.5h | 421.3h | 972.2h |
| Worker-classified human attention | 1.4h | 4.6h | 5.7h | 5.8h |
| Worker/headless AI generation | 3.9h | 89.5h | 132.6h | 230.9h |
| Additive observed work | 19.3h | 219.3h | 711.1h | 1,724.8h |
| Interactive sessions | 55 | 213 | 496 | 620 |
| Worker sessions | 283 | 919 | 1,799 | 3,044 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 90 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| grok-4.5 | 42,053 | 291.9M | 21.9M | 3,844.5M | 0 | 92.9% | 1,428 | 393.4h |
| MiniMax-M3.1-Flash | 8,593 | 15.1M | 1.8M | 1,239.3M | 0 | 98.8% | 108 | 25.5h |
| grok-4.6 | 8,256 | 69.6M | 3.2M | 901.1M | 0 | 92.8% | 74 | 45.8h |
| grok-4.7 | 6,814 | 29.0M | 1.3M | 634.3M | 0 | 95.6% | 233 | 30.8h |
| gpt-6.1-sol | 5,201 | 16.6M | 1.3M | 525.4M | 0 | 96.9% | 250 | 24.8h |
| minimax-m3.1-flash-free | 3,200 | 7.6M | 840K | 319.8M | 0 | 97.7% | 54 | 14.9h |
| gpt-5.6-sol | 3,110 | 11.3M | 739K | 316.7M | 0 | 96.6% | 201 | 13.0h |
| MiniMax-M3 | 195 | 377K | 21K | 22.3M | 0 | 98.3% | 5 | 0.6h |
| qwen3-14b-q4-k-m | 104 | 452K | 79K | 1.4M | 0 | 76.8% | 13 | 4.6h |
| deepseek-v4-pro | 62 | 484K | 10K | 9.4M | 0 | 95.1% | 6 | 0.2h |
| deepseek-flash | 16 | 234K | 3K | 3.1M | 0 | 93.1% | 1 | 0.0h |
| qwen3-14b-q4-k-m-nothink | 16 | 87K | 873 | 369K | 0 | 80.8% | 2 | 0.0h |
| claude-sonnet-5-5 | 4 | 0 | 0 | 0 | 0 | 0.0% | 4 | 0.0h |
| grok-4-5 | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| qwen3-vl-30b-a3b-q4-k-m | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **77,626** | **442.9M** | **31.3M** | **7,818.3M** | **0** | **94.6%** | **2,298** | **553.7h** |

_8,292.5M total tokens processed. 94.6% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| grok-4.5 | 52,073 | 397.6M | 27.4M | 5,359.7M | 0 | 93.1% | 1,634 | 467.1h |
| gpt-5.6-sol | 50,952 | 271.2M | 13.6M | 6,350.2M | 0 | 95.9% | 571 | 399.5h |
| grok-4.6 | 9,802 | 92.8M | 3.7M | 1,093.2M | 0 | 92.2% | 147 | 55.2h |
| MiniMax-M3.1-Flash | 8,593 | 15.1M | 1.8M | 1,239.3M | 0 | 98.8% | 108 | 25.5h |
| grok-4.7 | 6,821 | 29.1M | 1.3M | 634.5M | 0 | 95.6% | 235 | 30.9h |
| claude-sonnet-5 | 5,447 | 10K | 4.6M | 1,661.0M | 94.2M | 94.6% | 16 | 32.2h |
| gpt-6.1-sol | 5,201 | 16.6M | 1.3M | 525.4M | 0 | 96.9% | 250 | 24.8h |
| gpt-6-astra | 4,486 | 17.6M | 1.0M | 892.6M | 0 | 98.1% | 17 | 30.7h |
| gpt-5.6-terra | 4,485 | 32.8M | 944K | 202.2M | 0 | 86.0% | 389 | 18.1h |
| deepseek-v4-flash | 3,430 | 12.8M | 971K | 329.9M | 0 | 96.2% | 152 | 7.2h |
| minimax-m3.1-flash-free | 3,200 | 7.6M | 840K | 319.8M | 0 | 97.7% | 54 | 14.9h |
| grok-build-0.1 | 2,571 | 5.5M | 367K | 367.1M | 0 | 98.5% | 4 | 8.8h |
| gpt-6-sol | 1,212 | 6.0M | 310K | 221.6M | 0 | 97.3% | 10 | 8.6h |
| claude-sonnet-4-6 | 741 | 37 | 60K | 5.9M | 1.3M | 82.1% | 4 | 1.5h |
| deepseek-v4-pro | 689 | 2.2M | 173K | 95.8M | 0 | 97.7% | 9 | 3.0h |
| gpt-5.6-luna | 503 | 4.7M | 177K | 37.1M | 0 | 88.6% | 81 | 7.3h |
| MiniMax-M3 | 195 | 377K | 21K | 22.3M | 0 | 98.3% | 5 | 0.6h |
| grok-4.3 | 173 | 4.1M | 47K | 20.9M | 0 | 83.6% | 14 | 0.5h |
| big-pickle | 155 | 853K | 188K | 11.9M | 0 | 93.3% | 4 | 1.5h |
| qwen3-14b-q4-k-m | 108 | 465K | 82K | 1.5M | 0 | 76.7% | 15 | 5.9h |
| deepseek-flash | 69 | 526K | 22K | 9.9M | 0 | 95.0% | 3 | 0.2h |
| qwen3-14b-q4-k-m-nothink | 16 | 87K | 873 | 369K | 0 | 80.8% | 2 | 0.0h |
| gpt-6-astra-fast | 8 | 301K | 1K | 994K | 0 | 76.7% | 1 | 0.1h |
| claude-sonnet-5-5 | 4 | 0 | 0 | 0 | 0 | 0.0% | 4 | 0.0h |
| gpt-5.6-sol-pro | 2 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-5.6-terra-fast | 2 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3-ultra-free | 2 | 57K | 6 | 0 | 0 | 0.0% | 2 | 0.0h |
| nemotron-3.5-lightning-free | 2 | 29K | 3 | 28K | 0 | 49.0% | 2 | 0.0h |
| grok-4-5 | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| qwen2.5-vl-3b-q4-k-m | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| qwen3-vl-30b-a3b-q4-k-m | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **160,945** | **918.8M** | **59.1M** | **19,404.3M** | **95.5M** | **95%** | **3,557** | **1,144.2h** |

_20,477.9M total tokens processed. 95% cache hit rate._
<!-- STATS-END -->

## Projects

- **[bct2-website](https://github.com/ccastle13/bct2-website)** -- No description
<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ccastle13)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-11-02 23:02 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<!-- TOTAL-CONTRIBUTIONS-START -->
<div align="center">
  <a href="https://commit-history.com/ccastle13?metric=total" target="_blank" rel="noopener noreferrer">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/contributions/total-dark.svg" />
      <img alt="ccastle13's cumulative total GitHub contributions" src="assets/contributions/total-light.svg" width="960" />
    </picture>
  </a>
</div>

[Verify on commit-history.com](https://commit-history.com/ccastle13?metric=total) · [Chart data](assets/contributions/total.json)

Includes commits, issues, pull requests, reviews, repositories, and restricted contributions. Refreshed daily through the prior UTC day; commit-history.com may use a different refresh cutoff. GitHub controls link navigation—Ctrl/Cmd-click opens verification in a new tab.
<!-- TOTAL-CONTRIBUTIONS-END -->
