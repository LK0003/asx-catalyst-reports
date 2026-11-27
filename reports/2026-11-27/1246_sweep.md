# ASX Catalyst Sweep — 27 November 2026

**Scan time:** 12:46pm AEDT (Melbourne). **Previous report:** `reports/2026-11-27/1016_sweep.md`, actual window end W = ~10:14am (as stated in that report; approximate, not exact-minute). **Data timestamp:** TradingView screener queried 12:43pm AEDT, `update_mode: streaming`. **Relative volume:** TradingView relative volume — methodology unverified. **Liquidity rule:** traded value ≥ A$100,000 AND market cap ≥ A$5m.

*Research/screening tool only — not financial advice. Presents evidenced research; does not recommend buying, selling, entering, or exiting any position.*

**Reconciliation:** Screener rows: gainers 5 + losers 5 = 10; A 2 + B 0 + C 7 + D 0 + E 1 = 10.

## Category A — Confirmed liquid movers

| Ticker | Company | Price chg | Rel.vol (TV, unverified) | Traded value | Mkt cap (source) | Catalyst | Listing time | LISTING/CONTENT | Key risk |
|---|---|---|---|---|---|---|---|---|---|
| **LBL** | Laserbond | −16.39% (screener); ASX header shows −13.93% (within 5pp, no conflict) | 6.13 | A$162,934 | $72.58m (ASX header, verified) | **Negative trading-update surprise**, READ: 1H FY27 revenue guided $19.0–20.0m, below PCP, after soft Q1 not fully offset by Q2; 2H FY27 guided materially stronger; cash $4.8m at 31 Oct 2026 (up from $2.9m at 30 Jun 2026). [PDF](https://announcements.asx.com.au/asxpdf/20261127/pdf/0774s5ytyhbhm9.pdf) | 8:38am | LISTING verified; CONTENT read | 2H recovery depends on unconfirmed order ramp; new OEM contribution (Komatsu/Metal7) mostly FY28+ |
| **MHC** | Manhattan Gold | −15.38% (screener and header agree) | 8.43 | A$102,720 | $12.71m (ASX header, verified) | Signed binding term sheet: USFM Corp to earn up to 85% of Hook Lake (Nunavut) for US$1.5m cash + A$28m exploration over 3yrs; MHC retains 15% free-carried to BFS. READ. Nominally large deal ($30.2m) but MHC gives up majority interest in its own recently-drilled discovery (41.15m@4.66g/t Au etc., disclosed 20 Aug 2026) for modest near-term cash — plausible explanation for negative reaction despite a positive-sounding headline. [PDF](https://announcements.asx.com.au/asxpdf/20261127/pdf/0774p78nwycyj6.pdf) | 8:23am | LISTING verified; CONTENT read | Completion subject to formal agreements (~30 days); USFM is itself pending a reverse-merger into Nasdaq:VEEE — counterparty not yet a seasoned operator |

## Category B — Traded value ≥$100k but market cap not verified
None this scan.

## Category E — Data conflict
| Ticker | Traded value (screener) | Conflict | Status |
|---|---|---|---|
| **CAY** | A$131,286 | ASX header: marketCap **not available (−1)**, statusCode "CR", priceChangePercent −20.75% vs screener −15.38% (5.4pp gap, exceeds 5pp threshold). CAY's per-company ASX listing shows last announcement as "Trading Halt", 26/11/2026 9:32am — **no halt-lift/resumption notice found**, and no CAY announcement appears in today's (27/11) full listing. Header volume (5,201,957) is nonzero, so halt status is unresolved/ambiguous from available data. | Not counted as a confirmed liquid mover |

## Category C / D — below threshold or cap below $5m
C (traded value <$100k): 7 rows. Top 5 by traded value: ATT (+33.3%, A$22,321), FG1 (−15.4%, A$17,726), MEM (+33.3%, A$14,780), TYX (+25.0%, A$14,750), OMG (+16.7%, A$12,718).
D (verified cap <$5m): 0 rows.

## Non-ASX-native catalyst check
Searched for US federal court/agency action affecting ASX resource/critical-minerals names. Found web coverage (Earthjustice, undated in search excerpt) describing a US District Court ruling that kept the injunction on Dateline Resources' (DTR) Colosseum Mine in place and rejected a stay request from Dept. of Interior/Dateline. **Could not establish from search results whether this ruling is new since this report's window** — the article's date is not confirmed, and DTR's own ASX per-company listing (checked this run, 6 announcements over the past week) shows no filing referencing this matter; its only items today are a Director's Interest Notice (9:33am, see overlap table), a Chair's Address (11:41am) and Results of Meeting (12:38pm), neither price-sensitive nor about Colosseum. Flagged for a follow-up check against primary court-docket sources, not reported as confirmed news.

## Overlap evidence (previous window end W ≈10:14am → now 12:46pm; checked from 9:29am)
All price-sensitive announcements in range; 120 non-price-sensitive announcements in the same range, not individually assessed.

| Time | Ticker | Title | PS | idsId | Grep result | Classification |
|---|---|---|---|---|---|---|
| 9:29am | BMR | Placement | Y | 03171714 | `0936_full.md:225` | DEDUPLICATED |
| 9:32am | TCF | Trust Update | Y | 03171717 | no match | MISSED BY EARLIER REPORT (headline only, not read this run) |
| 9:33am | DTR | Change of Director's Interest Notice | Y | 03171718 | no match for this item | MISSED BY EARLIER REPORT (headline only, not read this run) |
| 9:38am | IFN | IFN AGM Addresses | Y | 03171723 | `1016_sweep.md:22` | DEDUPLICATED (headline only this run) |
| 9:38am | TVN | Tivan refers Speewah Fluorite Project under EPBC Act | Y | 03171722 | `1016_sweep.md:21` | DEDUPLICATED (headline only this run) |
| 9:40am | ARV | Drilling Progress and Sharon Dam Target | Y | 03171726 | `1016_sweep.md:20` | DEDUPLICATED; READ: maiden hole 26SDD001 broke through Nullarbor cover at 343.3m, continuing to ~750m target — no mineralisation result yet |
| 9:40am | RDM | (same document as ARV) | Y | 03171726 | `1016_sweep.md:20` | DEDUPLICATED; READ (same doc) |
| 9:43am | HWK | Final Hole Intersects Wide Copper-Gold Zone at Cactus | Y | 03171730 | `1016_sweep.md:19` | DEDUPLICATED; READ: DD26CT016 72.7m@0.72% Cu,0.08g/t Au from surface; 8/11 holes hit Cu-Au-Ag mineralisation, zone open |
| 9:48am | AM7 | Xinhai Agreement Executed to Fund Swanson Tantalum Mine | Y | 03171738 | `1016_sweep.md:18` | DEDUPLICATED; READ: binding JV, staged earn-in to 60% ORP by Xinhai, free-carry to AM7 during construction, placement priced at 173% premium to last close |
| 9:50am | DYM | New Gold Results Reinvigorate Redross Gold Prospect | Y | 03171743 | `1016_sweep.md:17` | DEDUPLICATED; READ: soil-geochem anomaly (Ultrafine+™) plus historical RC intercepts (e.g. 22m@0.90g/t Au) — target-generation stage, not new drilling |
| 9:50am | DYM | Multiple Gold Anomalies Identified at Princess Sally | Y | 03171742 | `1016_sweep.md:17` | DEDUPLICATED; READ: soil-in-gold anomalies (50–200ppb Au contours) — early-stage target generation |
| 9:51am | DYM | Response to ASX Price Query | Y | 03171744 | `1016_sweep.md:17` | DEDUPLICATED; READ: confirms assay results received 24 Nov ~1pm (around time of ASX query); no evidence of prior leak |
| 9:59am | NEU | Neuren updates on Pitt Hopkins Phase 3 development program | Y | 03171751 | `1016_sweep.md:16` | DEDUPLICATED; READ — **revises prior speculation**: FDA reiterated a trial design Neuren says requires a sample size "not executable" for Pitt Hopkins; Neuren is now pursuing an FDA "Rare Disease Framework" pathway with a written submission due Dec 2026 — a stall/delay for this specific program, not a confirmed Phase 3 pathway. Separate Phelan-McDermid Phase 3 (Neuren's main near-term catalyst) unaffected |
| 10:14am | PFT | Annual General Meeting Investor Presentation | Y | 03171761 | `1016_sweep.md:23` | DEDUPLICATED (at-cutoff-minute item; headline only this run) |
| 11:30am | BAK | Annual General Meeting Presentation | Y | 03171795 | no match | NEW; READ: reiterates prior resource-growth disclosure (20 Nov 2026) and Exploration Target of ~400–700Mt at a stated grade range; ASX header shows priceChange 0%, volume 117,012 |
| 11:39am | MMI | Senior Debt Restructure Update | Y | 03171801 | no match | NEW; READ: ~US$17.8m Nebari tranche moved to interest-only until Dec 2027 bullet payment; ~US$7.6m (~A$11.5m) cash-flow benefit Nov26–Jun27 funding Bauxite Hills Phase 2 screening |
| 11:47am | SDF | Results of Scheme Meeting | Y | 03171806 | no match | NEW; READ: Steadfast shareholders voted in favour of acquisition by Starboard BidCo (Dragoneer/KKR) |
| 11:59am | NOU | Implementation of Schemes of Arrangement | Y | 03171811 | no match | NEW; READ: scheme implemented, $0.1234/share paid, delisting effective 30 Nov 2026 |
| 12:18pm | TZL | Pause in Trading | Y | 03171826 | no match | NEW; READ (full, short doc): standard halt notice, no substance disclosed |
| 12:29pm | BM1 | AGM Presentation | Y | 03171834 | no match | NEW; READ: reiterates prior MRE (23 Sept 2026); no new resource figures found in extracted text |

## Source coverage

| Source | Status | Notes |
|---|---|---|
| ASX todayAnns listing | OK | curl, 287 rows, 7:30am–12:41pm, not truncated (no pagination markers found) |
| ASX per-company listing (CAY, MHC, DTR) | OK | Used for halt check (CAY), confirmation of no other announcements (MHC), litigation cross-check (DTR) |
| ASX header API (market cap/volume/price) | OK | LBL, CAY, MHC, BAK, TZL checked; CAY returned marketCap −1 |
| ASX documents | OK | 15 downloaded (HTTP 200), 15 text-extracted (pdftotext exit 0), 15 used as basis for "read" labels. 6 further price-sensitive items in-window (TCF, DTR-dir-notice, IFN, TVN, PFT) were not retrieved this run — over the prioritised 15-document budget — and remain headline-only |
| TradingView screener | OK | Both gainer/loser screens returned under limit (5 rows each), not truncated |
| TradingView news | Not used | Not needed — ASX primary documents covered all category A/overlap items |
| Web search (non-ASX-native catalysts) | Partial | Found undated secondary coverage on DTR/Colosseum; could not confirm as new vs. already-known; no corresponding DTR ASX filing found |

**Documents attempted (idsId \| ticker \| HTTP \| bytes \| extracted chars \| used):**
03171646|LBL|200|149663|9157|yes · 03171604|MHC|200|834739|39437|yes · 03171751|NEU|200|182990|10899|yes · 03171738|AM7|200|595956|50393|yes · 03171730|HWK|200|5466067|296759|yes · 03171726|ARV/RDM|200|889597|51661|yes · 03171743|DYM|200|4431830|236902|yes · 03171742|DYM|200|1495983|102588|yes · 03171744|DYM|200|393727|16221|yes · 03171795|BAK|200|4426221|127528|yes · 03171801|MMI|200|235554|7021|yes · 03171806|SDF|200|356577|11392|yes · 03171811|NOU|200|141025|4112|yes · 03171826|TZL|200|112631|528|yes · 03171834|BM1|200|3580182|43684|yes

Tools called outside Bash/Read/Write/Edit/Glob/Grep/WebFetch/WebSearch/ToolSearch and the TradingView read tools (run-screener, get-symbol-data, get-symbol-data-batch): none.

---
*Research/screening tool only. Not financial advice. Does not constitute a recommendation to buy, sell, enter, or exit any position.*
