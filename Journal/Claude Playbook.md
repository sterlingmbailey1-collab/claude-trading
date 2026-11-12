---
tags: [trading/journal, claude]
updated: 2026-11-12
---
# Claude Playbook

The standing rules and memory for Claude's trading study in the Robinhood MCP account (••3913). Every scan reads this and [[Claude Trading Log]] first, and updates them when something changes.

## Mandate
- Full control belongs to Claude (handed over 2026-11-12). No end date, no loss limit set by the user.
- The user's questions about Claude's thinking are speculative, not instructions; don't change strategy because of them. An explicit instruction (for example to stop) still applies.
- Fixed by the user: cash only, never borrow; trade only this account; no Anthropic stock (conflict of interest).

## What success means
1. **Beat SPY** on a time-weighted basis over the life of the study.
2. **Beat SMH** while the account is concentrated in chip stocks. If SMH beats the account over a full month, stock picking isn't adding value: change the approach (or just hold the fund).
3. **Process:** average winner larger than average loser; every exit rule honored.

Benchmarks start from the 2026-11-06 closes: SPY $735.29, SMH $463.96.

## Risk rules (Claude's own)
- **Per-trade risk:** size each position so that hitting its exit level loses at most 3% of the account (size = 3% of account ÷ distance to exit). Fractional positions can gap past an exit overnight, so lean smaller when overnight risk is high.
- **Order cap:** no single order larger than 50% of the account.
- **Headline risk:** a position with open company-specific risk stays at or below 15% of the account.
- Every position has a written exit level in the log, and it gets acted on.

## Lessons
Any scan adds a lesson whenever something deserves one: a winning or losing trade, a trade skipped that should have been taken (or the reverse), a rule that helped or failed, or a market surprise. Each lesson is one line, with the date and the trade or event behind it. Mention a new lesson in that scan's report. Update an old lesson instead of adding a duplicate, and mark one *retired* if later evidence shows it was wrong. The user likes this section, so keep it honest and specific.

1. Don't buy into an unresolved company crisis (open board or legal investigation, CEO's job in question). A quiet day is not resolution. *(NVDA, 2026-11-11)*
2. Trade with relative strength: when money rotates from a stock to its rivals, buy the rivals. *(SMH → AVGO worked; NVDA dip-buy failed)*
3. Never loosen an entry rule just to get cash invested.
4. After a 4%+ jump, buy in two halves at separate scans. *(ONTO 11-10 and AVGO/NVDA 11-11 were bought near the day's high)*
5. Fractional shares can't use stop orders or trade after hours; prefer whole shares (which can carry a real stop order) for positions with event risk when affordable.

## Pattern tracking
Goal: learn which signals actually work in this market, from the vault's daily scans and from my own trades, before trusting any of them.
- **Scan follow-through (Friday review):** for each trading day of the past week, take the top 10 names in that day's Daily Scans confluence list and record their 5-trading-day return against SPY over the same days (get_equity_historicals, 10 symbols per call) in `Journal/Signal Tracker.md`, grouped by the setup scan that qualified them (Oversold Bounce, RSI(2) Pullback, Momentum Breakout, ...). Also note how scan streaks behaved (names on Strong Uptrend or Weekly Trend Leaders several days running).
- **My own setups:** every trade in the log carries a setup tag ([news rotation], [earnings drift], [dip buy], [momentum], [core]). The Friday review totals results by tag.
- **Rules for using it:** nothing counts until a setup has at least 20 observations across at least 4 weeks (around mid-December). Compare against SPY and SMH, not zero. Decide what to test before looking at the numbers, and treat one good week as noise. Then, and only then, favor setups with a proven edge and drop the ones without.

## Sources
- **News:** Bigdata.com first (licensed outlets). Newsflash REST API via `curl -sS "https://newsflash.sh/api/events?q=...&min_sources=2&from=YYYY-MM-DD"`: the key is injected automatically (free tier, 1,000 requests a day); the Newsflash connector tool is still on the 50-a-day test tier. Echonews only as leads: its AI summaries are often wrong.
- **Vault notes** from the user's own scans (~8:19 AM, ~11:53 AM, ~4:07 PM, ~4:42 PM with the confluence list, ~8:09 PM): useful for ideas; verify their news.

## Schedule
Five scans each weekday (ET): 8:35 AM pre-market · 10:15 AM after the open · 12:05 PM midday · 3:25 PM before the close (last chance for fractional trades; decide what to hold overnight) · 4:50 PM after the close (scoreboard, watchlist, Friday weekly review).

## Catalyst calendar
| Date | Event | Why it matters |
|---|---|---|
| 2026-11-12 pm | AMAT and CSCO earnings | AMAT reads through to ONTO and chip equipment |
| 2026-11-17 pm | NVDA earnings | Moves every AI-chip holding; extra check at 6:15 PM |
| Before 11-26 | Anthropic IPO (reported) | May pull money from AI stocks around the listing; not tradable here |
| 2026-11-26 | Thanksgiving: market closed | Scans will find the market shut |
| 2026-11-27 | Early close at 1:00 PM | Extra pre-close check at 12:25 PM; the 3:25 PM scan runs after the close |
| 2026-12-09 pm | AVGO earnings | Largest holding's report |

## Watchlist
_Updated by the 4:50 PM scan: 2-4 names with the reason._
- **AMD**: likely home for the NVDA proceeds (direct Nvidia alternative; paired with Google's new TPU).
