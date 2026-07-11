<p align="center"><img src="https://gapmine.com/icon-512.png" width="88" alt="GapMine logo"></p>

<h1 align="center">GapMine — Market Gaps Dataset</h1>

<p align="center"><b>An open, continuously-updated dataset of unbuilt market gaps</b><br>
mined from real builder conversations on Reddit, Hacker News, Product Hunt and GitHub.</p>

<p align="center"><a href="https://gapmine.com">gapmine.com</a> · Updated 2026-07-11 · 231 gaps across 4 sectors · License: CC-BY-4.0</p>

---

## What this is

[GapMine](https://gapmine.com) continuously mines public builder conversations to surface **market gaps — real, unmet needs that nobody has built yet — before they get crowded.** This repository publishes that data as open, machine-readable JSON so it can be freely cited and analyzed. Every gap is a cluster of real people describing the same problem, graded by verifiable evidence — no AI-invented ideas.

## The data

| Sector | Gaps tracked | Builder signals | Links |
|---|---|---|---|
| **Developer and Tech Tools** | 96 | 336 | [Report ↗](https://gapmine.com/blog/state-of-tech-gaps-2026) · [JSON](data/tech-gaps.json) |
| **Ecommerce and DTC** | 51 | 398 | [Report ↗](https://gapmine.com/blog/state-of-ecommerce-gaps-2026) · [JSON](data/ecommerce-gaps.json) |
| **No-Code and Automation** | 47 | 210 | [Report ↗](https://gapmine.com/blog/state-of-nocode-gaps-2026) · [JSON](data/nocode-gaps.json) |
| **Creator Economy** | 37 | 203 | [Report ↗](https://gapmine.com/blog/state-of-creator-gaps-2026) · [JSON](data/creator-gaps.json) |

- **`data/<sector>-gaps.json`** — ranked opportunities with the audience asking, signal counts, and an evidence grade (`validated` / `corroborated` / `early`).
- Full written reports live on **[gapmine.com/blog](https://gapmine.com/blog)** (canonical source).

## Evidence grades

| Grade | Meaning |
|---|---|
| `validated` | 4+ signals across 2+ independent platforms |
| `corroborated` | 2+ signals |
| `early` | a fresh, single-platform signal worth watching |

## Citation

> GapMine — Market Gaps Dataset (2026-07-11). https://gapmine.com

Licensed **CC-BY-4.0**: free to use and cite with attribution to GapMine.
