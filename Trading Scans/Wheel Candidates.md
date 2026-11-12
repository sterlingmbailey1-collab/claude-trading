---
tags: [trading/scan, robinhood]
scan_id: d7e4e204-cb8e-48c8-923f-745af4e51372
category: Options income
bias: Neutral
timeframe: 30-day IV
created: 2026-11-11
---
# Wheel Candidates

Part of [[Robinhood Scans Index]].

**Category:** Options income · **Bias:** Neutral · **Timeframe:** 30-day IV

## Filters
- Implied volatility between 30% and 60%
- Last price between $10 and $60
- Options volume (1d) > 2,000
- Market cap > $2B
- Asset type = Stock

## What it finds
Affordable, liquid optionable stocks with decent premium: candidates for the wheel (sell cash-secured puts, then covered calls).

## How to trade it
Sell puts only on stocks you'd be happy to own. Pick strikes near support.

## How the bot should use it
Run weekly. Exclude names in [[Earnings This Week]].

Run it with `run_scan` and scan_id `d7e4e204-cb8e-48c8-923f-745af4e51372`.

## Risk
You can be assigned shares that keep falling. Premium doesn't protect against big drops.

## Log
- 2026-11-11: created, 109 matches at creation.
