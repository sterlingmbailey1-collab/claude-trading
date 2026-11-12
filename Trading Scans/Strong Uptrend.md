---
tags: [trading/scan, robinhood]
scan_id: bae59976-2eee-4919-82b1-791d18eed94c
category: Trend following
bias: Bullish
timeframe: Daily
created: 2026-11-11
---
# Strong Uptrend

Part of [[Robinhood Scans Index]].

**Category:** Trend following · **Bias:** Bullish · **Timeframe:** Daily

## Filters
- ADX (14, 1d) > 25
- RSI (14, 1d) between 50 and 70
- Asset type = Stock · Last price > $5 · Avg volume (30d) > 1M

## What it finds
Liquid stocks in an established trend that is not yet overbought.

## How to trade it
Buy pullbacks to the 20- or 50-day average while the trend holds. Trail a stop under swing lows.

## How the bot should use it
Returns a big list (377 at creation). Use it as a universe, then rank by relative volume or combine with another scan.

Run it with `run_scan` and scan_id `bae59976-2eee-4919-82b1-791d18eed94c`.

## Risk
ADX measures trend strength, not direction. RSI 50–70 tilts it bullish but doesn't guarantee it.

## Log
- 2026-11-11: created, 377 matches at creation.
