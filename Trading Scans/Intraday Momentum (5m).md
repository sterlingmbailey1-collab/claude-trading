---
tags: [trading/scan, robinhood]
scan_id: 63b112ea-3f89-4f41-ae43-09d7d3ca2da5
category: Momentum
bias: Bullish
timeframe: 5-minute
created: 2026-11-11
---
# Intraday Momentum (5m)

Part of [[Robinhood Scans Index]].

**Category:** Momentum · **Bias:** Bullish · **Timeframe:** 5-minute

## Filters
- % Change (5m) > 1%
- Volume (last 5m bar) > 100,000
- Last price > $5
- Asset type = Stock

## What it finds
Stocks making a sharp move in the latest 5-minute bar on heavy volume.

## How to trade it
Scalp continuation with a stop under the bar's low.

## How the bot should use it
Built for frequent polling during market hours. Results change every few minutes.

Run it with `run_scan` and scan_id `63b112ea-3f89-4f41-ae43-09d7d3ca2da5`.

## Risk
Noisy. Fast reversals are common and costs add up on frequent trades.

## Log
- 2026-11-11: created, 1 matches at creation.
