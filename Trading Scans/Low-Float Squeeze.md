---
tags: [trading/scan, robinhood]
scan_id: 38e1a31e-6d70-4ec7-89fd-4541114b77aa
category: Momentum
bias: Bullish
timeframe: Daily
created: 2026-11-11
---
# Low-Float Squeeze

Part of [[Robinhood Scans Index]].

**Category:** Momentum · **Bias:** Bullish · **Timeframe:** Daily

## Filters
- Float < 20M shares
- Relative volume (30d) > 3×
- % Change (1d) > 5%
- Last price > $1
- Asset type = Stock

## What it finds
Stocks with few tradable shares spiking on huge volume.

## How to trade it
Only for small, quick trades with tight stops. Take profits fast.

## How the bot should use it
Run in the first hour. No matches at creation. Keep position size tiny.

Run it with `run_scan` and scan_id `38e1a31e-6d70-4ec7-89fd-4541114b77aa`.

## Risk
Extremely volatile, thin liquidity and wide spreads. Prone to halts and pump-and-dump moves.

## Log
- 2026-11-11: created, 0 matches at creation.
