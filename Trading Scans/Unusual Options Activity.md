---
tags: [trading/scan, robinhood]
scan_id: 2715e320-75a8-4b1d-8b1f-b43697909b56
category: Options flow
bias: Neutral
timeframe: Daily
created: 2026-11-11
---
# Unusual Options Activity

Part of [[Robinhood Scans Index]].

**Category:** Options flow · **Bias:** Neutral · **Timeframe:** Daily

## Filters
- Relative options volume (30d) > 3×
- Options volume (1d) > 5,000

## What it finds
Stocks and ETFs where options trading is suddenly 3× its normal level, often ahead of news.

## How to trade it
Look at which strikes and expiries are active, then trade in the direction of the flow with defined risk.

## How the bot should use it
Run late in the session. Follow up with [[Heavy Call Buying]] / [[Heavy Put Buying]] to see the lean.

Run it with `run_scan` and scan_id `2715e320-75a8-4b1d-8b1f-b43697909b56`.

## Risk
Volume doesn't show whether trades were buys or sells, or hedges. Index ETFs (SPY, QQQ) appear often.

## Log
- 2026-11-11: created, 19 matches at creation.
