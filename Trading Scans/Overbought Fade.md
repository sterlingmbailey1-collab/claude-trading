---
tags: [trading/scan, robinhood]
scan_id: d2180a4a-be75-40d5-8537-6c8cdef5c8b6
category: Mean reversion
bias: Bearish
timeframe: Daily
created: 2026-11-11
---
# Overbought Fade

Part of [[Robinhood Scans Index]].

**Category:** Mean reversion · **Bias:** Bearish · **Timeframe:** Daily

## Filters
- RSI (14, 1d) > 75
- Asset type = Stock · Last price > $5 · Avg volume (30d) > 1M

## What it finds
Liquid stocks stretched to the upside that may pull back.

## How to trade it
Wait for a reversal sign (bearish engulfing, lower high) before shorting or buying puts. Or use it to take profits on longs.

## How the bot should use it
Run after the close. Skip names also in [[Weekly Trend Leaders]], since strong trends stay overbought.

Run it with `run_scan` and scan_id `d2180a4a-be75-40d5-8537-6c8cdef5c8b6`.

## Risk
Shorting has unlimited risk. Strong stocks can stay overbought for weeks.

## Log
- 2026-11-11: created, 54 matches at creation.
