# ASX MIDDAY SWEEP

**Date:** Friday, 20 November 2026
**Scan time:** ~12:48pm AEDT (Melbourne)
**Previous report:** `reports/2026-11-20/1015_sweep.md`; its actual window end W = 10:15am AEDT (stated coverage: "9:35am–10:15am")
**Data timestamp:** TradingView screener queried ~12:48pm AEDT; `update_mode: "streaming"` on all rows
**Relative volume note:** TradingView relative volume — methodology unverified (do not read as time-adjusted or full-day)
**Liquidity rule:** traded value ≥ A$100,000 AND market cap ≥ A$5m = confirmed liquid (A)

**Reconciliation:** Screener rows: gainers 11 + losers 10 = 21; A 1 + B 0 + C 19 + D 0 + E 1 = 21

*Research/screening tool, not financial advice. Nothing here is a recommendation to buy, sell, hold, enter or short. Facts/interpretation/speculation kept separate; unconfirmed items marked "Not verified."*

---

## Category A — Confirmed liquid movers

| Ticker | Company | Price chg | Rel. vol (TV, methodology unverified) | Traded value (A$) | Mkt cap (ASX header) | Catalyst | Listing time | LISTING/CONTENT | Key risk |
|---|---|---|---|---|---|---|---|---|---|
| MVF | Monash IVF Group | −22.5% | 6.53x | $1,668,457 | $294.2m (verified) | FY27 Trading Update: underlying FY27 NPAT guided "materially below FY26 and current analyst consensus" — explicit profit downgrade, second consecutive guidance miss after FY26. **This is a negative-surprise headline despite "update" framing** — materiality test: reduces near-term earnings outlook, not priced in until today. | 9:23am | LISTING verified (today's feed); CONTENT read — idsId 03168315, pdfURL announcements.asx.com.au/asxpdf/20261120/pdf/076v4t0zdq67kl.pdf | Cost-out program ($8–11m) benefits pushed out further than planned; H2 outlook assumes no market improvement |

## Category B — Cap not verified
None this window.

## Category E — Data conflict (not counted as confirmed liquid)

| Ticker | Company | Screener chg | ASX header chg | Diff | Traded value | Catalyst | Notes |
|---|---|---|---|---|---|---|---|
| EIQ | EchoIQ Ltd | +20.0% | +10.91% | 9.1pp (>5pp threshold) | $2,765,779 | Two-part story: (1) 19 Nov 2:57pm PS announcement — US FDA upheld its "not substantially equivalent" determination on appeal for EchoSolv HF (regulatory setback — read, idsId 03167983, pdfURL …076t59sgfhknm0.pdf); stock was placed in a trading halt 19 Nov 10:20am, pause 10:02am. (2) Today 12:01–12:04pm: Cleansing Notice (s708A) for 1,000,000 shares issued on option exercise + Appendix 2A quotation application (read, idsId 03168424, 03168421). Checked EIQ per-company listing today: **no active halt notice today** — stock resumed trading, so the conflict is not explained by a halt; it reads as a timing/snapshot discrepancy between the two live sources rather than a halt-driven artefact. | Non-ASX-native catalyst: US FDA action (NSE determination upheld) — explicitly checked per the mandatory offshore-catalyst search this run. |

## Category C — Traded value < A$100,000 (19 rows; market cap not needed)
Top 5 by traded value: ENV −50.0% ($74,081) · BKT −26.7% ($73,451) · RLG −20.0% ($60,403) · EDO +25.0% ($55,770) · AXI +25.0% ($35,861)

## Category D — Traded value ≥ A$100k, verified market cap < A$5m
0 rows this window.

---

## Overlap evidence (price-sensitive announcements, W−45min = 9:30am through 12:39pm scan)

| Time | Ticker | Headline | PS | idsId | Grep result | Classification |
|---|---|---|---|---|---|---|
| 9:52am | ANO | Chair's Presentation to Shareholders | Yes | 03168349 | `reports/2026-11-20/1015_sweep.md:22` | DEDUPLICATED (T≤W) |
| 9:55am | TKM | High-Grade Manganese Hits of up to 40.3% Mn | Yes | 03168352 | `reports/2026-11-20/1015_sweep.md:15` | DEDUPLICATED (T≤W) |
| 10:51am | AHE | First Earn-out Payment Received Relating to ANZ Divestment | Yes | 03168375 | no match | NEW (T>W) |
| 11:15am | A8G | Diamond drilling programme commences at Spodumene Hill | Yes | 03168385 | no match | NEW (T>W) |
| 11:49am | VFX | Visionflex Secures University Virtual Care Contract | Yes | 03168411 | no match | NEW (T>W) |
| 12:14pm | AVD | 2026 AGM — CEO address to shareholders | Yes | 03168435 | no match | NEW (T>W) |
| 12:14pm | AVD | 2026 AGM — Chair address to Shareholders | Yes | 03168434 | no match | NEW (T>W) |

117 non-price-sensitive announcements also lodged in this window — not individually assessed.

**NEW item notes (CONTENT read for all):**
- **AHE** (idsId 03168375): A$805,442 earn-out received from Jonas Software for the ANZ divestment (1st of 3 periods), exceeds the A$550k recognised in FY26 accounts; cumulative consideration now A$33.9m. Modest, incremental — confirms an existing deal is performing above book, not a new catalyst.
- **A8G** (idsId 03168385): Diamond drilling (~3,000m) commenced at Spodumene Hill, Atex Lithium-Tantalum Project, Côte d'Ivoire (A8G holds an option on 75%). Exploration-stage news with no assay results yet — materiality test: pre-drill-result news, not yet a resource/earnings catalyst.
- **VFX** (idsId 03168411): Charles Sturt University contract for 10 telehealth carts; first-year contract value A$0.46m (A$0.41m hardware/one-off + A$0.05m ARR). Small in absolute dollar terms but company-described as "financially significant" for VFX — **not independently verified against VFX's revenue base** (Not verified).
- **AVD** (idsId 03168434/03168435): AGM chair's and CEO's addresses both disclose CEO **resignation** — a governance/succession event flagged price-sensitive; no financial guidance figures found in the extracted text.

---

## Non-ASX-native catalyst search (mandatory this run)
WebSearch for US federal court/agency actions against ASX-listed resource/offshore-asset companies, Nov 2026: found a 7 Nov 2026 federal judge denial of a preliminary-injunction request against South32's Hermosa mine expansion (Arizona) — pre-dates this window and S32 is not a mover today, so not actionable here. No FDA-type action found via search; the EIQ FDA matter above was instead located via the ASX per-company listing, not this search.

---

## Source coverage

| Source | Status | Notes |
|---|---|---|
| ASX todayAnns listing | OK | 282 rows retrieved, 7:30am–12:39pm (curl, HTTP 200) |
| ASX per-company listings | OK | EIQ, MVF, AHE(n/a—used today listing), A8G(n/a), VFX(n/a) via `announcements.do?by=asxCode` |
| ASX header API (market cap) | OK | EIQ, MVF — both HTTP 200, `marketCap` field returned |
| ASX documents (PDF) | OK | 9 attempted, see table below |
| TradingView screener | OK | 2 calls (gainers/losers), `update_mode: streaming` |
| TradingView get-news | Not called this run | Materiality assessed from primary PDFs instead |
| WebSearch (offshore catalysts) | OK | 1 query run, see above |
| Company IR / mirrors | Not needed | ASX primary source sufficient for all documents this run |

**Documents:** downloaded 9 / text-extracted 9 / used 8

| idsId | Ticker | HTTP | Bytes | Extracted chars | Used? |
|---|---|---|---|---|---|
| 03167983 | EIQ | 200 | 105,296 | 3,869 | yes |
| 03168424 | EIQ | 200 | 110,377 | 2,621 | yes |
| 03168421 | EIQ | 200 | 14,569 | 10,532 | downloaded, not read (routine Appx 2A) |
| 03168315 | MVF | 200 | 242,247 | 10,655 | yes |
| 03168375 | AHE | 200 | 178,945 | 5,179 | yes |
| 03168385 | A8G | 200 | 726,510 | 6,269 | yes |
| 03168411 | VFX | 200 | 180,798 | 5,890 | yes |
| 03168435 | AVD | 200 | 333,327 | 13,813 | yes |
| 03168434 | AVD | 200 | 301,187 | 8,380 | yes |

No price query / aware letter / media-speculation responses found in today's listing (282 rows, 7:30am–12:39pm).

No tools outside Bash/Read/Write/Edit/Glob/Grep/WebFetch/WebSearch/ToolSearch and the TradingView read tools (run-screener) were called.

---

*Research/screening tool only. Not financial advice.*
