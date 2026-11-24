# ASX SWEEP — 24 Nov 2026, scan actually run ~12:43–12:50pm AEDT (Melbourne)

**Previous report:** `reports/2026-11-24/1015_sweep.md`. Its own text states its window as "to ~10:12am AEDT" — no more precise cutoff given, so **W = 10:12am**, taken from its stated window end, not the scheduled slot.
**Data timestamp:** TradingView screener queried ~12:46pm AEDT; `update_mode` = "streaming" on all returned rows.
**Relative volume:** `relative_volume_10d_calc` = TradingView relative volume — methodology unverified (not described as time-adjusted or full-day).
**Liquidity rule:** traded value (close×volume, A$) ≥ $100,000 AND market cap ≥ A$5m = CONFIRMED LIQUID (A). Cap unobtainable = CAP NOT VERIFIED (B). Traded value <$100k = C. Verified cap <$5m = D. Volume/change conflict with ASX header = E.
**Reconciliation:** Screener rows: gainers 17 + losers 5 = 22; A 5 + B 1 + C 14 + D 0 + E 2 = 22.

This is a research/screening tool, not financial advice; nothing here is an instruction to act.

## Category A — CONFIRMED LIQUID

| Ticker | Chg (screener) | Rel.vol (TV, unverified) | Traded value A$ | Mkt cap | Catalyst (LISTING/CONTENT flags inline) |
|---|---|---|---|---|---|
| BPM | −32.98% | 4.74× | $882,807 | $36.8m, header matches | Clyde RC follow-up assays (Forelands gold, WA): new holes 9m@5.05g/t, 8m@1.61g/t, 5m@1.56g/t — well below the already-disclosed flagship intercept (4m@20.57g/t incl. 1m@73.33g/t). Positive-sounding headline, but new numbers read as a likely negative surprise vs. the earlier benchmark (INTERPRETATION). LISTING verified 9:36am idsId 03169620; CONTENT read, pdftotext 71,446 chars, [PDF](https://announcements.asx.com.au/asxpdf/20261124/pdf/076zby0h26s9xg.pdf) |
| SLM | −25.00% | 16.07× | $192,962 | $10.6m, header matches | "First Cucho Drill Hole Extends Copper System" — Cucho has only visual/qualitative sulphide observations, assays pending; Cinto modest 0.57%Cu/2m; Mandacaru Li low-grade 0.18% Li2O. No hard new grade numbers despite upbeat framing. LISTING verified 9:18am idsId 03169584; CONTENT read, 90,190 chars, [PDF](https://announcements.asx.com.au/asxpdf/20261124/pdf/076z8c6422h4wq.pdf) |
| CML | +17.65%/+17.65% | 4.55× | $152,529 | $24.6m, header matches | "Exceptional High-Grade Niobium" — Bailundo (Angola) maiden holes 81.6m@1.5% Nb2O5 incl. 53.2m@2.02%, and 83.2m@1.5% incl. 25.75m@2.41%. Concrete strong new assays. LISTING verified 8:58am idsId 03169548; CONTENT read, 205,889 chars, [PDF](https://announcements.asx.com.au/asxpdf/20261124/pdf/076z5rwt3tshrw.pdf) |
| RCR | +54.55%(scr)/+63.64%(hdr) | 125.3× | $597,258 | $5.74m, header | "Outstanding High-Grade Copper-Gold at Telfer South" — 21m@2.40g/t Au & 3.83% Cu from surface, new zone. Change% conflicts >5pp between sources; no halt found, likely snapshot-timing mismatch not a halt. LISTING verified 8:58am idsId 03169549; CONTENT read, 85,875 chars, [PDF](https://announcements.asx.com.au/asxpdf/20261124/pdf/076z5v1s9zqct4.pdf) |
| SKM | +21.57%(scr)/+17.65%(hdr) | 6.46× | $642,581 | $41.68m, header | UNEXPLAINED — RESEARCH REQUIRED. ASX per-company page states "No announcements were released by SKM" this week; newest TradingView news dated 8 Nov, nothing today. LISTING: no matching announcement found in the retrieved listing (366 rows, 7:30am–12:40pm); CONTENT not accessed. Change% differs scr-vs-hdr by 3.92pp (<5pp, not classed E) |

## Category B — CAP NOT VERIFIED (never merged into A)

| Ticker | Chg | Rel.vol (TV, unverified) | Traded value A$ | Mkt cap | Catalyst (LISTING/CONTENT inline) |
|---|---|---|---|---|---|
| 1TT | +150% | 106.7× | $127,428 | Not verified — ASX header API HTTP 400 "Symbol not found"; no other source succeeded | **UNEXPLAINED — RESEARCH REQUIRED.** No entry in today's full listing or 1TT's weekly per-company listing (last filings: AGM results 20 Nov, Appendix 4C 19 Nov); newest TradingView news is a 20 Oct proposed 30:1 share consolidation. A +150% move with no identified driver found. LISTING: no matching announcement found in the retrieved listing (366 rows, 7:30am–12:40pm); CONTENT not accessed |

## Category E — DATA CONFLICT (never counted as confirmed movers)

| Ticker | Screener chg/vol | ASX header chg/vol | Conflict | Halt check | Catalyst |
|---|---|---|---|---|---|
| KAL | −15.38%, vol 79,230,288 | 0%, vol 0 (price matches: 0.011) | Volume 0 vs ~79m; change 0% vs −15.38% | No halt; page states **no announcements released in the past week**; newest TradingView news 13 Sep | UNEXPLAINED — RESEARCH REQUIRED. Header volume/change fields look stale for this illiquid stock; no catalyst found anywhere |
| RCR | — listed here only for the conflict; full entry and verified catalyst are in Category A above | | | | |

## Category C — traded value <A$100,000 (count only, no catalyst research performed)

14 rows. Top 5 by traded value: SUH $91,467 (+17.86%); ENV $74,081 (−50.00%); IRI $50,419 (−16.98%); M96 $42,960 (+60.00%); PKY $41,201 (+25.00%).

## Category D — verified market cap <A$5m

0 rows this scan.

## Overlap — price-sensitive announcements, W−45min (9:27am) through scan time (last row 12:40pm)

Window re-checked per production rule. 180 total rows in window; 45 price-sensitive (each row below); 135 non-price-sensitive (not individually assessed, count only).

| Time | Ticker | Headline | idsId | Grep result | Classification |
|---|---|---|---|---|---|
| 9:28am | ALY | Iron Ore JV Advances Development Studies | 03169600 | no match | MISSED BY EARLIER REPORT |
| 9:28am | OMX | BC8: Strategic Consolidation around Kal East | 03169597 | no match | MISSED BY EARLIER REPORT |
| 9:28am | BC8 | Strategic Consolidation around Kal East | 03169597 | no match | MISSED BY EARLIER REPORT |
| 9:29am | SHN | New high-grade vein set at Sybil confirmed by sampling | 03169602 | no match | MISSED BY EARLIER REPORT |
| 9:29am | ARX | Aroa Biosurgery H1 FY27 Results | 03169601 | 0935_full.md:155 | DEDUPLICATED |
| 9:30am | ARX | Aroa Half Year Results Presentation | 03169606 | no match (0935_full.md:155 covers the results release, not this slide pack) | MISSED BY EARLIER REPORT |
| 9:30am | AR1 | Enterprise Pays Off in Copper Rewards | 03169604 | no match | MISSED BY EARLIER REPORT |
| 9:32am | IMA | Binding Agreements Signed for Durack and Yandanooka Projects | 03169613 | 0935_full.md:99-109 | DEDUPLICATED |
| 9:32am | ESR | Drilling Encounters Manganese and Export Update | 03169610 | 0935_full.md:187 | DEDUPLICATED |
| 9:33am | BPG | BPG H1 FY27 Results — Moving decisively to profitability | 03169615 | 0935_full.md:75,153 | DEDUPLICATED |
| 9:34am | BOT | Botanix allowed additional US Patent Claims | 03169616 | no match | MISSED BY EARLIER REPORT (non-ASX-native catalyst: US Patent Office action) |
| 9:36am | RWC | Major Shareholder Support for the Scheme Received | 03169622 | 1015_sweep.md:28 | DEDUPLICATED |
| 9:36am | BPM | Clyde Continues to Deliver with Further High-Grade Gold | 03169620 | 1015_sweep.md:36 (ticker only, in a grouped row; title not individually covered) | DEDUPLICATED |
| 9:37am | TRI | TRI Submits Ethics Application for Stabl-Im Phase 1 Study | 03169624 | 1015_sweep.md:36 (grouped) | DEDUPLICATED |
| 9:38am | VKA | Viking Achieves Further Ore Sorting Success at Linka | 03169628 | 1015_sweep.md:36 (grouped) | DEDUPLICATED |
| 9:38am | ANT | Tecomatlan Produces Est. 20t of Antimony Concentrate | 03169627 | 1015_sweep.md:36 (grouped) | DEDUPLICATED |
| 9:39am | MPW | MPW Investor Presentation | 03169631 | no match (1015_sweep.md:33 covers the placement doc, not this presentation) | MISSED BY EARLIER REPORT |
| 9:39am | MPW | MPW Completes A$7.5 Million Placement | 03169630 | 1015_sweep.md:33 | DEDUPLICATED |
| 9:40am | SBK | Acquisition of Ruhizha Tungsten Project, Uganda | 03169635 | 1015_sweep.md:36 (grouped) | DEDUPLICATED |
| 9:40am | BKT | Early Works Funding Received from CRDB | 03169634 | 1015_sweep.md:36 (grouped) | DEDUPLICATED |
| 9:43am | SDF | Update on Scheme of Arrangement | 03169637 | 1015_sweep.md:29 | DEDUPLICATED |
| 9:45am | AM3 | 45.8m @ 5.88g/t Gold in Down-Dip Extension Hole at Apollo | 03169640 | 1015_sweep.md:31 | DEDUPLICATED |
| 9:48am | SMX | Initial Grade Control Drilling at Zelica | 03169642 | 1015_sweep.md:36 (grouped) | DEDUPLICATED |
| 9:52am | BTE | Serowe CBM Project Update | 03169646 | 1015_sweep.md:36 (grouped) | DEDUPLICATED |
| 9:55am | CMA | Update on Carma's Bailment Finance Facility | 03169650 | 1015_sweep.md:36 (grouped) | DEDUPLICATED |
| 9:57am | LML | Acquisition of copper exploration licence in NSW | 03169653 | 1015_sweep.md:35 | DEDUPLICATED |
| 9:59am | DTM | Yamarna Gold-Lithium Project Acquisition Completion | 03169659 | 1015_sweep.md:30 | DEDUPLICATED |
| 10:02am | SUH | Due Diligence Commenced - Potential Sale of Llahuin Project | 03169665 | 1015_sweep.md:34 | DEDUPLICATED |
| 10:09am | AX8 | Manganese Rock Chips to 53.7% and Drilling Update | 03169674 | 1015_sweep.md:32 | DEDUPLICATED |
| 10:10am | PCI | Dividend/Distribution - PCI | 03169677 | no match | MISSED BY EARLIER REPORT (routine dividend notice, low materiality) |
| 10:17am | KRM | Penikat Area 6 - Permit and Enforcement Order Appeal | 03169681 | n/a — lodged after W | NEW |
| 10:20am | GCI | Dividend/Distribution - GCI | 03169682 | n/a — lodged after W | NEW |
| 10:22am | TRP | Company Update | 03169687 | n/a — lodged after W | NEW |
| 11:00am | CCG | 2026 AGM - Chair's Address to Shareholders | 03169710 | n/a — lodged after W | NEW |
| 11:01am | CCG | 2026 AGM - Presentation to Shareholders | 03169712 | n/a — lodged after W | NEW |
| 11:04am | MPP | Metroglass provides 1H27 results (unaudited) | 03169714 | n/a — lodged after W | NEW |
| 11:06am | MPP | Metroglass FY27 Interim Financial statements | 03169716 | n/a — lodged after W | NEW |
| 11:10am | MPP | MPG NZX results form | 03169720 | n/a — lodged after W | NEW |
| 11:11am | AAM | AAM Discovers Porphyry System at Cape Ray | 03169721 | n/a — lodged after W | NEW |
| 11:21am | KMD | KMD Brands update on discussions with Bluestar Alliance | 03169730 | n/a — lodged after W | NEW |
| 11:32am | KSC | KSC Limited Earnings Update | 03169737 | n/a — lodged after W | NEW |
| 11:42am | PPK | Chair's Address and Presentation | 03169742 | n/a — lodged after W | NEW |
| 11:49am | SRN | Share Placement and Option Issues | 03169743 | n/a — lodged after W | NEW |
| 11:56am | NHC | Hybrid Securities Offer open and Replacement Prospectus | 03169751 | n/a — lodged after W | NEW |
| 12:27pm | LRV | Hillgrove Mine Modification 5 Update | 03169768 | n/a — lodged after W | NEW |

NEW items are headline-only this scan; none cross-checked against consensus/guidance. KMD and AAM look worth a closer read next scan given headline materiality (INTERPRETATION of headline only).

## Non-ASX-native catalyst check (done this scan)

WebSearch for US federal court/DOJ/agency action affecting ASX resource companies today found no result dated 24 Nov 2026. Neither DTR (Dateline Resources) nor USC (US1 Critical Minerals) — the tickers involved in the previously-flagged Colosseum/Mojave federal court matter — lodged any ASX announcement today (checked against the 366-row listing). No new ruling confirmed this scan.

## Source coverage

| Source | Status | Detail |
|---|---|---|
| ASX todayAnns listing | OK | curl, HTTP 200, 648,821 bytes, 366 rows, 7:30am–12:40pm (newest-first; retrieved ~12:44pm, rows after 12:40pm simply hadn't lodged yet) |
| ASX per-company listings | OK | 8 tickers (BPM, SKM, AMD, SLM, CML, 1TT, KAL, RCR), all HTTP 200 |
| ASX header API (mkt cap) | Partial | 7/8 succeeded; 1TT HTTP 400 "Symbol not found" |
| ASX documents | OK | Downloaded 4/4, text extracted 4/4, used 4/4 |
| TradingView screener | OK | 2 calls, 17+5=22 rows, neither truncated (limit 40) |
| TradingView news | OK | AMD, SKM, 1TT, KAL — no items dated today for any |
| WebSearch (non-ASX catalyst) | OK | No result dated today |
| Company IR / mirrors | Not needed | ASX primary source sufficed |

**Document table:**

| idsId | Ticker | pdfURL | HTTP | Bytes | Extracted chars | Used? |
|---|---|---|---|---|---|---|
| 03169620 | BPM | announcements.asx.com.au/.../076zby0h26s9xg.pdf | 200 | 2,259,683 | 71,446 | Yes |
| 03169584 | SLM | announcements.asx.com.au/.../076z8c6422h4wq.pdf | 200 | 3,318,750 | 90,190 | Yes |
| 03169548 | CML | announcements.asx.com.au/.../076z5rwt3tshrw.pdf | 200 | 3,491,487 | 205,889 | Yes |
| 03169549 | RCR | announcements.asx.com.au/.../076z5v1s9zqct4.pdf | 200 | 2,385,099 | 85,875 | Yes |

No tools outside Bash/Read/Write/Edit/Glob/Grep/WebFetch/WebSearch/ToolSearch and the TradingView read tools (run-screener, get-symbol-data, get-news) were called this scan: none.
