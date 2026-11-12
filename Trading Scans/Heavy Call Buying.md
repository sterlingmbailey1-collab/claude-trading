---
tags: [trading/scan, robinhood]
scan_id: 011d771d-d0da-48e4-81f4-f77931c035e6
category: Options flow
bias: Bullish
timeframe: Daily
created: 2026-11-11
---
# Heavy Call Buying

Part of [[Robinhood Scans Index]].

**Category:** Options flow · **Bias:** Bullish · **Timeframe:** Daily

## Filters
- Call volume (1d) > 20,000
- Relative options volume (30d) > 2×

## What it finds
Names with heavy call volume and above-normal total options activity.

## How to trade it
Compare with [[Heavy Put Buying]]. Names on this list but not that one lean bullish.

## How the bot should use it
Run late in the session.

Run it with `run_scan` and scan_id `011d771d-d0da-48e4-81f4-f77931c035e6`.

## Risk
Overlaps heavily with [[Heavy Put Buying]] at creation (mega caps and index ETFs). It can't tell buyers from sellers.

## Log
- 2026-11-11: created, 28 matches at creation.
