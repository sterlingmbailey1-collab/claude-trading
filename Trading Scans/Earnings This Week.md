---
tags: [trading/scan, robinhood]
scan_id: 4356d6e7-b47c-4fdb-b373-91740fcb7a93
category: Event
bias: Neutral
timeframe: Next 7 days
created: 2026-11-11
---
# Earnings This Week

Part of [[Robinhood Scans Index]].

**Category:** Event · **Bias:** Neutral · **Timeframe:** Next 7 days

## Filters
- Earnings date within the next 0–7 days
- Asset type = Stock

## What it finds
Stocks reporting earnings in the coming week (Robinhood's Upcoming Earnings preset).

## How to trade it
Avoid opening new swing trades into earnings, or trade the event on purpose with defined-risk options.

## How the bot should use it
Run at the start of each week. Use it as a do-not-hold filter for the other scans.

Run it with `run_scan` and scan_id `4356d6e7-b47c-4fdb-b373-91740fcb7a93`.

## Risk
Earnings moves are binary. Implied volatility usually collapses right after the report.

## Log
- 2026-11-11: created, 319 matches at creation.
- 2026-11-12: re-sorted by market cap (largest first). Robinhood returns at most 200 rows, and the old earnings-date sort was cutting off the current day's reporters. For a full list, use `get_earnings_calendar`.
