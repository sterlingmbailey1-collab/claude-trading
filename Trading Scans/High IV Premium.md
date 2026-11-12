---
tags: [trading/scan, robinhood]
scan_id: 00ba9410-8ed2-4335-958f-252880b856d0
category: Options income
bias: Neutral
timeframe: 30-day IV
created: 2026-11-11
---
# High IV Premium

Part of [[Robinhood Scans Index]].

**Category:** Options income · **Bias:** Neutral · **Timeframe:** 30-day IV

## Filters
- Implied volatility (30d ATM) > 60%
- Options volume (1d) > 5,000
- Last price > $10

## What it finds
Liquid optionable stocks where options are expensive, which favors selling premium.

## How to trade it
Sell defined-risk premium (credit spreads, iron condors) rather than buying options.

## How the bot should use it
Check [[Earnings This Week]] first. High IV before earnings is expected, not a mispricing.

Run it with `run_scan` and scan_id `00ba9410-8ed2-4335-958f-252880b856d0`.

## Risk
High IV means the market expects big moves. Short premium can lose quickly if a big move comes.

## Log
- 2026-11-11: created, 167 matches at creation.
