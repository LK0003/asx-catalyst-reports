# ASX POST-CLOSE SWEEP

**Date:** Monday, 28 September 2026
**Scan time:** ~16:35 AEST (Melbourne), post the ~4:00pm close
**Cutoff reference:** This afternoon's [15:45 full report](1545_full.md)
**Purpose:** Lightweight delta scan for anything new/material since 3:45pm, plus closing-price context for the top catalysts.

**Access note (unchanged across today's report series):** Direct `WebFetch` to asx.com.au, marketindex.com.au, fool.com.au, tipranks.com, raskmedia.com.au and other primary/secondary sites returned blocked/`EGRESS_BLOCKED` again this run. This sweep is built entirely from `WebSearch` snippet synthesis — no live intraday/closing price feed or primary ASX announcement PDF was directly accessible.

---

## New announcements/halts since 3:45pm

**Nothing new or material found.** Multiple targeted searches (ASX trading-halt lists, price-sensitive announcement queries, time-boxed "4:00pm/4:30pm" searches) returned no company announcement, halt, or disclosure with a timestamp inside the 3:45pm–4:35pm window. No confirmed new price-sensitive items for NST, KAR, INA, PAR, AMD, or any other ticker in this window.

---

## Closing-price context for today's top 3 catalysts

| Ticker | 3:45pm report estimate | Post-close finding | Verified? |
|---|---|---|---|
| **NST** | ~+9% to ~A$23.95 | Search snippets conflict: figures range from +7.1% (~A$23.68) to +11% (~A$24.46), with no source explicitly labelling a figure as the 4pm close | **Not verified** — treat prior +9%/A$23.95 estimate as indicative only |
| **KAR** | ~-12% to ~A$1.57 | Multiple independent secondary sources converge on ~-12.6% to ~A$1.56 | Close to prior estimate; consistent across sources but still not explicitly sourced as a primary-confirmed closing print |
| **INA** | ~+6.67% (move reported, no price level) | Figure of +6.67%/$4.80 explicitly qualified by one source as a **midday** price, not a close | **Not verified** as a closing price |

**ASX 200:** One single-sourced, uncorroborated figure puts the index up ~0.2% to ~8,680 — not cross-confirmed, treat as indicative only.

## PAR / AMD status

- **PAR (Paradigm Biopharmaceuticals):** No evidence found that today's committed funding-implications update has been published. Still reported in voluntary suspension. **Not verified** as released as of this scan.
- **AMD (Arrow Minerals):** No confirmation the halt (since 24 Sept) has been lifted or that its reason has been disclosed today. **Not verified** — status unchanged from the 3:45pm report.

---

*This is a research/screening report, not financial advice. It presents evidenced research and does not recommend buying, selling, entering, exiting, or any other trading action.*
