---
tags: [trading/scan, robinhood]
scan_id: 9bdf7815-69a3-43ad-9d6e-974976d10afa
category: Mean reversion
bias: Bullish
timeframe: Daily
created: 2026-11-11
---
# RSI(2) Large-Cap Pullback

Part of [[Robinhood Scans Index]].

**Category:** Mean reversion · **Bias:** Bullish · **Timeframe:** Daily

## Filters
- RSI (2, 1d) < 10
- Market cap > $10B
- Asset type = Stock

## What it finds
Large caps with a sharp 1–3 day pullback (a classic short-term mean-reversion setup).

## How to trade it
Buy near the close; exit when RSI(2) goes back above 50–70 or after a few days.

## How the bot should use it
Run near the close. Works best on names that are also in [[Weekly Trend Leaders]].

Run it with `run_scan` and scan_id `9bdf7815-69a3-43ad-9d6e-974976d10afa`.

## Risk
Fails in strong downtrends and market-wide selloffs.

## Log
- 2026-11-11: created, 17 matches at creation.
