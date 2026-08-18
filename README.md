# Obsidian Terminal

A desktop trading journal for gold (XAUUSD), built by a discretionary intraday trader to replace the spreadsheet he had outgrown.

https://github.com/user-attachments/assets/091748db-cf06-467a-a1fb-397d88d393a7

> Everything shown in the video runs on demo data.

## Why

Excel is good with numbers. It is not good at showing you what you actually did.

Comparing one trading day against another was never easy. So I built the tool that does it — a horizontal view of my own trading, days against days and months against months, to find the behaviours worth repeating and the ones worth killing.

## What it does

- **Journal** — daily trade log with automatic ingestion from MetaTrader 5, chart viewer with zoom and side-by-side comparison. Every trade is scored on two axes: was the zone valid, was the moment right. Those two scores place the trade in a quadrant, judged separately from the money.
- **Pins** — visual anchors. You mark what you saw on the chart — a slowdown, a sweep, a rejection — and you name it. Months later you pull that name and get every day the same thing showed up.
- **Dashboard** — accumulated P&L, win rate broken down by trade quality, cost per mistake label, performance by day, behaviour calendar.
- **Strategy Browser** — a taxonomy of your own concepts. Stack days, compare them, turn them into a hypothesis.
- **Gold Replay** — manual bar-replay backtester: one year of 15-second candles (~1.42M bars), candle and sub-candle stepping, drawing tools, persisted sessions, simulated trade tracker.
- **AI reviews** — narrative weekly and monthly reports generated from the trade history against a playbook distilled from it.
- **Guardian** — a live discipline brake. It polls the broker and, past your daily loss limit, takes over the screen and forces a pause. Discipline does not slip all at once. It slips one trade at a time.
- **Canvas** — free-form board to relate days and concepts visually.
- **Multi-device** — the same app from a phone as a PWA over a private network.

## Stack

| Layer | Tech |
|---|---|
| Frontend | React 19 · Vite · TypeScript · Tailwind |
| Backend | FastAPI · SQLite · Python 3.14 |
| Desktop | Tauri 2 |
| Data | MetaTrader 5 integration · Dukascopy tick data |

## Status

v2.0.x, in daily use. Active development.

## Source code

Closed source, privately owned. **This repository is a showcase — it contains no source code.**

© 2026 Máximo Sckell. All rights reserved.

## Contact

- LinkedIn — [máximo-sckell](https://www.linkedin.com/in/máximo-sckell-02a42b233)
- GitHub — [@msckell](https://github.com/msckell)
- Email — maximosck@gmail.com
