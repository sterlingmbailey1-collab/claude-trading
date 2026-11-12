---
tags: [trading/journal]
---
# Trade Journal

Log one note per trade in this folder, named like `2026-11-12 NVDA Oversold Bounce`. Copy [[Trade Entry Template]] (or set `Templates/` as your template folder in Obsidian: Settings → Core plugins → Templates).

Fill in **Plan** before entering and **Review** after exiting. The frontmatter fields (setup, r_multiple, pnl) let you compare setups later, for example with the Dataview community plugin:

```dataview
TABLE setup, direction, r_multiple, pnl, status
FROM "Journal" WHERE ticker
SORT date DESC
```

See also: [[Indicator Glossary]] · [[Robinhood Scans Index]]
