---
tags: [trading/scan, robinhood]
created: 2026-11-11
---
# Robinhood Scans Index

All 20 market scans saved in Robinhood on 2026-11-11. Each note has the exact filters, the scan_id and how to use it.

These are screening ideas, not investment advice. Thresholds are common starting points, not backtested values.

| Scan | Category | Bias | Timeframe |
|------|----------|------|-----------|
| [[Oversold Bounce]] | Mean reversion | Bullish | Daily |
| [[Momentum Breakout]] | Momentum | Bullish | Daily |
| [[Gap Up]] | Momentum | Bullish | Daily (open) |
| [[Strong Uptrend]] | Trend following | Bullish | Daily |
| [[Unusual Options Activity]] | Options flow | Neutral | Daily |
| [[Quality Value]] | Fundamental | Bullish | Long-term |
| [[Earnings This Week]] | Event | Neutral | Next 7 days |
| [[Crypto Movers]] | Momentum | Bullish | Daily |
| [[Overbought Fade]] | Mean reversion | Bearish | Daily |
| [[Breakdown on Volume]] | Momentum | Bearish | Daily |
| [[Low-Float Squeeze]] | Momentum | Bullish | Daily |
| [[High IV Premium]] | Options income | Neutral | 30-day IV |
| [[Intraday Momentum (5m)]] | Momentum | Bullish | 5-minute |
| [[RSI(2) Large-Cap Pullback]] | Mean reversion | Bullish | Daily |
| [[Weekly Trend Leaders]] | Trend following | Bullish | Weekly |
| [[Heavy Call Buying]] | Options flow | Bullish | Daily |
| [[Heavy Put Buying]] | Options flow | Bearish | Daily |
| [[Wheel Candidates]] | Options income | Neutral | 30-day IV |
| [[ETF Big Movers]] | Momentum | Neutral | Daily |
| [[High-Margin Leaders]] | Fundamental | Bullish | Long-term |

## Daily results
A scheduled task runs these scans every weekday after the close (about 4:30–4:45 PM ET). It writes a ranked note to `Daily Scans/YYYY-MM-DD.md` and the full data to `Daily Scans/data/YYYY-MM-DD.csv`. It skips the Intraday Momentum (5m) scan, which only makes sense during market hours. Every ticker that hits a scan gets a note in `Tickers/` with its scan history. Write your own thoughts under **My notes** in a ticker note; the daily run won't overwrite them.

## Vault map
| Folder | What's in it | Updated |
|---|---|---|
| `Trading Scans/` | One note per scan: filters, how to trade it, risks | When scans change |
| `Daily Scans/` | Daily note: market context, confluence, top 10 per scan. `data/` holds the full CSV and research JSON | Weekdays |
| `Tickers/` | One note per ticker that hit a scan: scan history and latest research | Weekdays |
| `Briefings/` | One note per day with Pre-market (8:16 AM), Midday (11:43 AM), After-close (4:05 PM) and Evening (8:09 PM, Sun–Thu) sections | 4× per day |
| `News/` | Daily log of market-moving headlines, linked to tickers (written by the 4:05 PM run) | Weekdays |
| `Account/` | Daily snapshot of positions, open orders and P&L (no account numbers) | Weekdays |
| `Journal/` | Your trade notes. See [[Journal]] | When you trade |
| `Reference/` | [[Indicator Glossary]] | As needed |
| `Templates/` | [[Trade Entry Template]] | As needed |

## Bot workflow
1. Start of week: run [[Earnings This Week]] and treat those names as do-not-hold.
2. Build the universe from [[Weekly Trend Leaders]], [[Quality Value]] and [[High-Margin Leaders]].
3. Daily: run the setup scans (bounces, breakouts, fades) and prefer names that are also in the universe.
4. Options: use [[High IV Premium]] / [[Wheel Candidates]] for selling and the flow scans for direction hints.
5. Note what worked in each scan's **Log** section so the thresholds can be tuned later.

## Editing scans
The Robinhood connector can create and edit scans but not delete them. To delete one, use Legend.

## Weekly reviews
- [[2026-W46]] (2026-11-11 → 2026-11-13)
