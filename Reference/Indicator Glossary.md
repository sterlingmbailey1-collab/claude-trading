---
tags: [trading/reference]
---
# Indicator Glossary

Plain-English definitions of every measure used in [[Robinhood Scans Index|the scans]] and daily notes.

## Price & volume
- **Last**: the most recent trade price.
- **% Change**: today's move compared with yesterday's close. Stored as a ratio in the CSVs (0.05 = 5%).
- **Gap**: how far today's open is from yesterday's close. Big gaps usually follow news.
- **Volume**: shares (or contracts) traded today.
- **Average volume (30d)**: typical daily volume over the last 30 days. Used as a liquidity floor.
- **Relative volume (RVOL)**: today's volume ÷ the average. Above 2× means unusual interest.
- **Float**: shares available for public trading. A small float (under 20M) can move violently.
- **Market cap**: share price × shares outstanding. Large cap is over $10B, mid cap $2–10B, small cap under $2B.

## Momentum & trend
- **RSI (14)**: a 0–100 score of recent gains vs losses. Under 30 = oversold, over 70 = overbought. In strong trends it can stay extreme for a long time.
- **RSI (2)**: a very short-term RSI. Under 10 marks a sharp 1–3 day dip, which is a classic mean-reversion trigger in large caps.
- **ADX (14)**: trend *strength*, not direction. Under 20 = no trend, over 25 = trending, over 40 = very strong.
- **MACD**: the gap between a fast and a slow moving average. Crossovers signal momentum shifts.
- **Moving averages (20/50/200-day)**: average closing price over N days. Price above a rising 50/200 is a healthy uptrend.
- **VWAP**: the average price paid today, weighted by volume. Intraday traders treat it as fair value.
- **Bollinger Bands**: a moving average ± 2 standard deviations. Narrow bands (a "squeeze") often come before big moves.

## Options
- **Implied volatility (IV)**: the yearly move the options market is pricing in. 60% IV ≈ an expected ±60%/yr (about ±3.8% per day for one standard deviation). High IV = expensive options.
- **Historical volatility (HV)**: how much the stock actually moved. IV well above HV means options are rich.
- **Options volume / open interest**: contracts traded today / contracts still open.
- **Relative options volume**: today's options volume ÷ its 30-day average. Above 3× is unusual.
- **Call/put volume**: calls profit if the price rises, puts if it falls. But volume can't tell buyers from sellers, and puts are often hedges.
- **IV crush**: the drop in IV right after an event like earnings.

## Fundamentals
- **P/E**: price ÷ earnings per share. Low P/E = cheap, or troubled.
- **Forward P/E**: price ÷ *expected* earnings.
- **PEG**: P/E ÷ growth rate. Under 1 suggests growth at a fair price.
- **ROE**: profit ÷ shareholder equity. Above 15% is strong.
- **Gross / operating / net margin**: profit left after cost of goods / operating costs / everything. High margins signal pricing power.

## Market context
- **VIX**: expected 30-day S&P 500 volatility, often called the "fear gauge." Under 15 = calm, 20–30 = nervous, over 30 = fear.
- **10-year Treasury yield**: when it rises, high-valuation growth stocks usually come under pressure.
- **Sector ETFs (XLK, XLF, …)**: show which parts of the market are leading or lagging (rotation).
- **Breadth**: how many stocks are rising vs falling. Narrow rallies led by a few names are fragile.
