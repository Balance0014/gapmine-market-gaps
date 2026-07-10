<p align="center">
  <img src="https://gapmine.com/icon-512.png" width="88" alt="GapMine logo">
</p>

<h1 align="center">GapMine — Market Gaps Dataset</h1>

<p align="center"><b>An open, continuously-updated dataset of unbuilt market gaps</b><br>
mined from real builder conversations on Reddit, Hacker News, Product Hunt and GitHub.</p>

<p align="center">
  <a href="https://gapmine.com">gapmine.com</a> ·
  Updated 2026-07-10 ·
  231 gaps across 4 sectors ·
  License: CC-BY-4.0
</p>

---

## What this is

[GapMine](https://gapmine.com) continuously mines public builder conversations to surface **market gaps — real, unmet needs that nobody has built yet — before they get crowded.** This repository publishes that data as open, machine-readable JSON so it can be freely cited and analyzed.

Every gap is a **cluster of real people describing the same problem**, graded by verifiable evidence. There are no AI-invented ideas and no opaque scores — each entry traces back to public source discussions.

## The data

| Sector | Gaps tracked | Builder signals | Links |
|---|---|---|---|
| **Developer and Tech Tools** | 97 | 354 | [Report ↗](https://gapmine.com/blog/state-of-tech-gaps-2026) · [JSON](data/tech-gaps.json) |
| **Ecommerce and DTC** | 50 | 397 | [Report ↗](https://gapmine.com/blog/state-of-ecommerce-gaps-2026) · [JSON](data/ecommerce-gaps.json) |
| **No-Code and Automation** | 46 | 206 | [Report ↗](https://gapmine.com/blog/state-of-nocode-gaps-2026) · [JSON](data/nocode-gaps.json) |
| **Creator Economy** | 38 | 204 | [Report ↗](https://gapmine.com/blog/state-of-creator-gaps-2026) · [JSON](data/creator-gaps.json) |

- **`data/<sector>-gaps.json`** — the ranked opportunities for each sector, with the audience asking, signal counts, and an evidence grade (`validated` / `corroborated` / `early`).
- **`data/summary.json`** — cross-sector totals.
- Full written reports live on **[gapmine.com/blog](https://gapmine.com/blog)** (the canonical source).

## How the evidence grade works

| Grade | Meaning |
|---|---|
| `validated` | 4+ signals across 2+ independent platforms |
| `corroborated` | 2+ signals |
| `early` | a fresh, single-platform signal worth watching |

We grade by evidence you can verify — never by an invented 0–100 score.

## Methodology

GapMine ingests public conversations from **Reddit, Hacker News, Product Hunt and GitHub**, clusters them by the underlying need, and grades each cluster on demand, supply gap and timing. Every claim traces to a public source. See the full method at [gapmine.com/how-it-works](https://gapmine.com/how-it-works).

## Citation

> GapMine — Market Gaps Dataset (2026-07-10). https://gapmine.com

Licensed **CC-BY-4.0**: free to use and cite with attribution to GapMine.
