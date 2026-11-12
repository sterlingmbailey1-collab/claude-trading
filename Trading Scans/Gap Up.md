---
tags: [trading/scan, robinhood]
scan_id: 1aa97eb6-b746-4c4f-9587-d1ca5a7cc7e1
category: Momentum
bias: Bullish
timeframe: Daily (open)
created: 2026-11-11
---
# Gap Up

Part of [[Robinhood Scans Index]].

**Category:** Momentum · **Bias:** Bullish · **Timeframe:** Daily (open)

## Filters
- Gap (1d) > 4%
- Relative volume (30d) > 1.5×
- Last price > $5
- Asset type = Stock

## What it finds
Stocks that opened well above yesterday's close with above-normal volume, usually on news.

## How to trade it
Gap-and-go: buy a break of the opening-range high. Gap-fill fade: short a failure back below the open.

## How the bot should use it
Run 5–15 minutes after the open. Check the catalyst with a news tool before acting.

Run it with `run_scan` and scan_id `1aa97eb6-b746-4c4f-9587-d1ca5a7cc7e1`.

## Risk
Gaps without a real catalyst often fill. No market-cap filter, so small names can show up.

## Log
- 2026-11-11: created, 2 matches at creation.
