# own-activity-calendar

Public dockit for **Own Development Log Part 3**: a homepage activity calendar that uses the familiar contribution-graph shape — built as **own HTML/CSS** in a Zero-DB PHP CMS, with **zero external widget**.

**Canonical article:**  
https://vpnstronger.com/own-activity-calendar-familiar-shape-zero-external-widget

**Live surface:** scroll past the category directory on https://vpnstronger.com — the **Activity** block.

This repo is not a library to install. It is a place to discuss the idea and ask “why not just embed GitHub / npm / Cursor?”

## Stance

- Familiar visual language is fine; importing someone else’s contribution graph is not required.
- Counts come from **our** published pages (first live / created day, UTC) — not a third-party API.
- No GitHub embed, no Cursor scrape, no heatmap npm package, no third-party script.
- **94 is not 100:** snapshot of first-live stamps, not a full edit-history audit.
- Zero-DB / OwnStack pattern: borrow the mental model, own the durable path.

## What it is (short)

| | |
|---|---|
| **Is** | Server-rendered HTML + CSS grid on homepage render |
| **Is** | Intensity = how many pages first landed that UTC day + streak / most-active stats |
| **Is not** | Contribution embed, external origin, supply-chain widget |

## Open questions (for Discussion)

1. Is “looks like GitHub” worth it if readers assume it’s a real GitHub graph?
2. First-live day only — enough for a publishing calendar, or should edits bump intensity too?
3. Should similar OwnStack UIs stay zero client JS by default, or is a tiny local script OK later?
4. Better sibling metaphor: contribution calendar, or something less brand-associated?
5. How do you keep independence when the *shape* is culturally tied to one vendor?

Use **Discussions**. Disagree with the article; bring alternatives. No drive-by “just use library X” without owning the dependency cost.

## Related (sister OwnStack dockits)

- Homemade 15s/30s candles: https://github.com/zsza83/homemade-15s-30s-candles  
  Article: https://vpnstronger.com/homemade-15s-30s-candles-own-stack-micro-tf-94-is-not-100
- Own-stack market data: https://github.com/zsza83/own-stack-market-data  
  Article: https://vpnstronger.com/own-stack-market-data-for-daytrade-bots-json-is-too-slow-what-instead
- Series hub: https://vpnstronger.com/series/own-development-log

Same pattern: clear model → own implementation → honest limits.

## License / tone

Public analysis dockit. Canonical truth stays on vpnstronger.com. Correct us in Discussion if the live homepage behavior changes.