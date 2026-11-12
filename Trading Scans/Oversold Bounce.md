---
tags: [trading/scan, robinhood]
scan_id: 0edc2ea6-8b17-4a25-aeec-5e0a8ad56a62
category: Mean reversion
bias: Bullish
timeframe: Daily
created: 2026-11-11
---
# Oversold Bounce

Part of [[Robinhood Scans Index]].

**Category:** Mean reversion · **Bias:** Bullish · **Timeframe:** Daily

## Filters
- RSI (14, 1d) < 30
- Asset type = Stock · Last price > $5 · Avg volume (30d) > 1M

## What it finds
Liquid stocks that have been sold hard and are statistically stretched to the downside.

## How to trade it
Wait for a reversal sign (green day, close above prior high) before entering. Stop below the recent low; target a move back to the 20-day average.

## How the bot should use it
Run after the close. Cross-check with [[Quality Value]] or [[Weekly Trend Leaders]] to prefer dips in strong names.

Run it with `run_scan` and scan_id `0edc2ea6-8b17-4a25-aeec-5e0a8ad56a62`.

## Risk
Oversold can stay oversold. Stocks falling on bad news (earnings miss, downgrade) often keep falling.

## Log
- 2026-11-11: created, 64 matches at creation.
