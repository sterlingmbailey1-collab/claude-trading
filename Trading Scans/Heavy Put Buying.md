---
tags: [trading/scan, robinhood]
scan_id: 68cfbe23-c929-4496-93a0-e473b5da692f
category: Options flow
bias: Bearish
timeframe: Daily
created: 2026-11-11
---
# Heavy Put Buying

Part of [[Robinhood Scans Index]].

**Category:** Options flow · **Bias:** Bearish · **Timeframe:** Daily

## Filters
- Put volume (1d) > 20,000
- Relative options volume (30d) > 2×

## What it finds
Names with heavy put volume and above-normal total options activity.

## How to trade it
Names here but not on [[Heavy Call Buying]] lean bearish, or are being hedged.

## How the bot should use it
Run late in the session.

Run it with `run_scan` and scan_id `68cfbe23-c929-4496-93a0-e473b5da692f`.

## Risk
Puts are often hedges, not bets on a fall. It can't tell buyers from sellers.

## Log
- 2026-11-11: created, 19 matches at creation.
