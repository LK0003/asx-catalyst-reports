# ASX MIDDAY SWEEP

**Date:** Thursday, 26 November 2026 **Scan time:** 12:49pm AEDT (Melbourne)
**Previous report:** `reports/2026-11-26/1015_sweep.md` — window end W=**~10:20am** (its own wording was imprecise: "covers ~9:35–10:20am," "as of 10:20am," but also "9:35–10:25am batch"; W=10:20am used, imprecision flagged per rule).
**Data timestamp (screener):** 12:44pm AEDT query; `update_mode: streaming` on all returned rows.
**TradingView relative volume — methodology unverified.**
**Liquidity rule:** traded value ≥ A$100,000 AND market cap ≥ A$5m.

Research/screening tool only. Not financial advice — no buy/sell/entry/exit view is given.

## Reconciliation
Screener rows: Gainers 7 + Losers 8 = 15. A 4 + B 1 + C 10 + D 0 + E 0 = 15. ✔ matches T.

## Category A — CONFIRMED LIQUID (traded value ≥A$100k, market cap verified ≥A$5m)

| Ticker | Company | Price chg | TV relvol (unverified) | Traded value (A$) | Mkt cap (ASX header) | Verified catalyst | Listing time | LISTING/CONTENT + source | Key risk |
|---|---|---|---|---|---|---|---|---|---|
| TTT | Titomic Ltd | +39.2%/+42.1%(hdr) | 4.05 | $1,800,140 | $159.5m | IDIQ sole-source subcontract, ceiling USD250m (AUD375m) to 31 Dec 2031, from an unnamed "major US aerospace and defense prime" (hypersonics/missile/aerospace). | 8:24am | LISTING✓; CONTENT read — idsId 03170890, announcements.asx.com.au/asxpdf/20261126/pdf/0772sd030dsl0p.pdf | Ceiling ≠ guaranteed revenue; actual task orders/margin undisclosed; TTT's past US defence deals were US$250k–$5m, so scale scepticism stands |
| DGR | DGR Global Ltd | +17.5% (matches hdr) | 6.93 | $896,627 | $41.7m | Samuel Holdings announced takeover intention at $0.045 cash/share (41% premium to undisturbed $0.032; 43% to 30/90-day VWAP). Samuel Holdings' sole director, Nicholas Mather, is DGR's own MD. | 9:15am | LISTING✓; CONTENT read — idsId 03170966, .../0772yxfrjhc4ts.pdf | Related-party bid (bidder controlled by DGR's own MD); DGR's close ($0.047) trades *above* the $0.045 offer — market may expect a higher/competing bid |
| AXL | Axel REE Ltd | +26.0% (matches hdr) | 21.58 | $120,513 | $8.8m | Auger drilling hit high-grade REE/gallium from surface outside the existing 709Mt@1,443ppm TREO/576Mt@35ppm Ga resource at Caladão, Brazil; best 18m@5,451ppm TREO, open at depth. | 8:25am | LISTING✓; CONTENT read — idsId 03170901, .../0772t4g8y8rcs3.pdf | Surface auger only, no resource update yet — company frames it as input to a *future* MRE |
| JNS | Janus Electric Holdings | -15.2%/-14.8%(hdr) | 2.41 | $1,079,960 | $124.7m | Completed A$15m placement: 27,272,727 shares at $0.55, a 15.6% discount to last traded $0.652 (pre-halt 24 Nov), ~11–13% discount to 5-day VWAP. | 9:46am | LISTING✓; CONTENT read — idsId 03171029, .../07733dx0ybpvdg.pdf | Move matches discount/dilution mechanics, not a surprise operating catalyst |

## Category B — CAP NOT VERIFIED (separate; never "liquid")

| Ticker | Company | Price chg | TV relvol (unverified) | Traded value (A$) | Mkt cap | Catalyst | Listing time | LISTING/CONTENT |
|---|---|---|---|---|---|---|---|---|
| CAY | Canyon Resources Ltd | -31.58% (matches hdr exactly) | 26.20 | $164,829 | **Not verified** — header returned `marketCap: 0` (likely post-raise data gap, not a genuine zero; header volume 5,339,577 vs screener 6,339,577 also disagree by ~1.0m shares, but change% matches exactly, so not classed E) | **Correction to earlier reports:** the 8:18–9:32am series (idsId 03170850 etc.) is not just a capital raise — Canyon has **withdrawn** the Minim Martap DFS outcomes and Ore Reserves (SRK-assisted review found rail/rolling-stock delays + higher ocean freight would cut production materially for ≥3 years), alongside a 1-for-1 renounceable entitlement offer at $0.034/share to raise ~$70m. Earlier 0935/1015 reports scored this "Score 55" as likely-positive without reading the withdrawal. Today's -31.58% (post-halt reinstatement 9:32am) is consistent with genuine negative fundamental news plus 1:1 dilution, not dilution alone. | 8:18–9:32am | LISTING✓; CONTENT read — idsId 03170850, .../0772pmd7dq0zrl.pdf |

## Category E — none this scan.

## Category C (traded value <A$100k) — count 10, top 5 by traded value
SNS $86,692 (+33.33%) · AEV $82,575 (+25.00%) · ADA $76,908 (-85.47%) · DYM $71,210 (-21.82%) · OZM $47,007 (+16.07%)
(Remaining 5: FIN $40,204, NOR $30,121, INF $21,286, AN1 $18,317, QUE $4,050 — not individually researched.)

**SNS note** (sub-$100k TV but also a NEW overlap item): signed a City of Chicago mobile-enforcement contract — AUD$1.37m upfront, AUD$1.91m ARR, ~AUD$1.88m to FY27 revenue, 24mth term +2×12mth options. LISTING✓ 11:51am; CONTENT read, idsId 03171155. Material vs SNS's small revenue base; explains the +33% move.

**ADA note** (-85.47%): not researched this run (sub-$100k TV) — **UNEXPLAINED – RESEARCH REQUIRED** if picked up again; magnitude flagged despite being below the liquidity threshold.

## Category D — count 0.

## Overlap evidence (window: 9:35am–12:44pm, i.e. W−45min through scan time; W=10:20am per above)

42 price-sensitive announcements fell in this window. Items with listing time T ≤ 10:20am were checked against earlier reports; items with T > 10:20am are NEW. Non-price-sensitive items in the window are not listed row by row (145 such rows, not individually assessed).

| Ticker | Time | Title | idsId | Grep result | Classification |
|---|---|---|---|---|---|
| STX | 9:36am | South Erregulla Power Plant Update | 03171011 | 1015_sweep.md:31 (grouped) | DEDUPLICATED |
| BPG | 9:37am | Reinstatement to Quotation | 03171014 | no match (0935_full.md covers a *different* BPG item, 9:24am placement-completion) | **MISSED BY EARLIER REPORT** — read: suspension lifted following BPG's capital raising; administrative only, no new financial facts |
| NWH | 9:37am | Fredon Contract Awards | 03171013 | 1015_sweep.md:31 (grouped) | DEDUPLICATED |
| LIO | 9:38am | Carbonate Target Reached | 03171016 | 1015_sweep.md:31 (grouped) | DEDUPLICATED |
| SWT | 9:39am | Distribution for month ending 30 Nov 2026 | 03171020 | no match | **MISSED BY EARLIER REPORT** — read: routine monthly ETF distribution, $0.009/unit, ~100% franked; no commercial significance |
| RCL | 9:41am | FY26 Full Year Results Presentation | 03171025 | 1015_sweep.md:31 (grouped, "RCL FY26 result") | DEDUPLICATED |
| RAP | 9:41am | High-Grade Copper Results — Chester | 03171024 | 1015_sweep.md:31 (grouped) | DEDUPLICATED |
| RCL | 9:46am | FY26 Full Year Results Release | 03171032 | 1015_sweep.md:31 (grouped) | DEDUPLICATED |
| JNS | 9:46am | Janus Electric completes A$15m private placement | 03171029 | 1015_sweep.md:31 (grouped, "JNS placement") | DEDUPLICATED (also see Category A above — same event, now read in full) |
| OZM | 9:46am | Placement to Advance Mulgabbie North | 03171028 | 1015_sweep.md:31 (grouped) | DEDUPLICATED |
| SOP | 9:47am | Synertec 2026 AGM Chair/MD Address | 03171035 | 1015_sweep.md:31 (grouped) | DEDUPLICATED |
| SMX | 9:47am | Binding Agreement Signed to Sell Biranup Project | 03171034 | 1015_sweep.md:26 | DEDUPLICATED — read: SMX sells 80% of Biranup to unlisted Manta Minerals, **conditional on Manta's own IPO**; consideration only $235k cash + 2.5m Manta shares (~$500k) + 1–2% NSR. Low-moderate materiality, not the "meaningful balance-sheet event" the headline alone implied. |
| EPY | 9:47am | Chairman Address to Shareholders | 03171033 | 1015_sweep.md:31 (grouped, "EPY AGM addresses") | DEDUPLICATED |
| EPY | 9:48am | 2026 AGM CEO Presentation | 03171040 | 1015_sweep.md:31 (grouped) | DEDUPLICATED |
| VR1 | 9:48am | Vection Signs $1.2m agreement | 03171039 | 1015_sweep.md:31 (grouped) | DEDUPLICATED |
| BOA | 9:48am | High-Grade Copper Results — Neds Creek | 03171037 | 1015_sweep.md:31 (grouped) | DEDUPLICATED |
| EPY | 9:48am | CEO Address to Shareholders | 03171036 | 1015_sweep.md:31 (grouped) | DEDUPLICATED |
| AMK | 9:50am | AMK Commences Ground Magnetics | 03171048 | no match | **MISSED BY EARLIER REPORT** — read: early-stage, no results yet; magnetics survey commenced, auger rigs being imported — preparatory news only |
| NXD | 9:52am | 2026 AGM Chair & CEO Addresses | 03171050 | 1015_sweep.md:31 (grouped) | DEDUPLICATED |
| NEU | 9:53am | Pause in Trading | 03171053 | 1015_sweep.md:27 | DEDUPLICATED |
| RCM | 9:53am | Trading Halt | 03171052 | 1015_sweep.md:28 | DEDUPLICATED (still unresolved — no reason disclosed as of 12:44pm) |
| FAU | 9:53am | Javelin Share Offer — Minimum Acceptance Fulfilled | 03171051 | 1015_sweep.md:25 | DEDUPLICATED |
| XRA | 9:57am | Executive Director Appointment | 03171059 | 1015_sweep.md:31 (grouped) | DEDUPLICATED |
| MPK | 9:58am | Ferke South Exploration Permit Granted | 03171060 | 1015_sweep.md:24 | DEDUPLICATED |
| G50 | 10:07am | MD's Address to the AGM | 03171069 | 1015_sweep.md:31 (grouped) | DEDUPLICATED |
| G50 | 10:07am | Chairman's Address to the AGM | 03171068 | 1015_sweep.md:31 (grouped) | DEDUPLICATED |
| NEU | 10:09am | Trading Halt | 03171071 | 1015_sweep.md:27 (at-cutoff-adjacent; T<W) | DEDUPLICATED (still unresolved — no reason disclosed as of 12:44pm) |
| SRR | 10:15am | Sarama Provides Update on Arbitration and Riedel Exploration | 03171077 | 1015_sweep.md:29 | DEDUPLICATED — but newly read this run (prior left "Not verified"): damages sought **updated to US$245.3m** +interest (was US$242m); Merits Hearing confirmed 22–26 Feb 2027; Burkina Faso's final response due 1 Dec 2026; Riedel began recon drilling at Cosmo early Nov 2026 (first in 30+yrs); Sarama holds ~32% of Riedel (scope to 44%). |
| MXI | 10:48am | On-Market Share Buy-Back Program | 03171106 | n/a — T>W | NEW — read: buyback ≤5,554,456 shares (<10% of capital), funded from FY26 opcashflow $29.8m; routine, low materiality. |
| AUV | 10:54am | AGM Investor Presentation | 03171111 | n/a — T>W | NEW — not individually read (routine AGM) |
| QGL | 10:55am | 2026 AGM Presentation | 03171114 | n/a — T>W | NEW — not individually read (routine) |
| SKS | 10:56am | AGM 2026 CEO Address | 03171115 | n/a — T>W | NEW — not individually read (routine) |
| GOW | 11:05am | Shopping Centre Debt Refinancing $97.5 Million Facility | 03171120 | n/a — T>W | NEW — read: Gowing Bros *refinanced* (not new) Pacific Coast Shopping Centres debt, St George/Westpac, $97.5m, 4yr, LVR 60%, ICR 1.5. Risk removed, no growth catalyst. |
| EGY | 11:24am | EGY Announcement Accelerated N R Entitlement Offer | 03171132 | n/a — T>W | NEW — read: **resolves EGY's 9:18am halt** (unexplained since 0935/1015 reports) — 1-for-1 accelerated non-renounceable entitlement at $0.02/share + $0.04 options, ~$12.49m for debt reduction/working capital, not underwritten, JLMs Shaw & Partners/Bell Potter. |
| EGY | 11:24am | EGY Capital Raise Presentation | 03171133 | n/a — T>W | NEW — same event as above, not separately read |
| EGY | 11:24am | EGY ANREO Prospectus | 03171134 | n/a — T>W | NEW — same event as above, not separately read |
| VML | 11:29am | Appointment of Chief Executive Officer | 03171136 | n/a — T>W | NEW — read: Rodney Ambrosie appointed CEO eff. 30 Nov, prior Nechalacho-project consulting history. Routine leadership news. |
| FEI | 11:38am | Distribution Details 30 November 2026 | 03171143 | n/a — T>W | NEW — not individually read (routine distribution) |
| FRA | 11:38am | Distribution Details 30 November 2026 | 03171143 | n/a — T>W | NEW — not individually read (shares idsId with FEI, stapled announcement) |
| PIC | 11:44am | Three fully franked monthly dividends | 03171150 | n/a — T>W | NEW — not individually read (routine) |
| SNS | 11:51am | Multimillion-dollar Contract with City of Chicago | 03171155 | n/a — T>W | NEW — read, see Category C note above |
| AXN | 12:13pm | MD's AGM Presentation | 03171177 | n/a — T>W | NEW — not individually read (routine) |

## Trading-halt carry-forward check (LEG, BAK, LAC, EGY)
Re-checked today's full listing (411 rows, 7:30am–12:41pm): **LEG** (8:54am), **BAK** (9:04am), **LAC** (9:07am) each still show only the original single "Trading Halt" notice — **still Not verified**, no reason disclosed as of 12:44pm. **EGY** (halted 9:18am) is now resolved — see the 11:24am entitlement-offer row above.

## Non-ASX-native (US court/agency) catalyst check
Web search run this scan for a dated US federal court/DOJ/DOD/FAST-41 development affecting an ASX critical-minerals/resource name: no ruling or agency action dated 26 November 2026 was found. Background items surfaced (Ioneer/Rhyolite Ridge March 2026 court win, Dateline Resources' ongoing DOJ-assisted defence of Colosseum Mine rights, South32 Hermosa FAST-41 completion in July 2026) are all pre-existing and not today's news. Sarama Resources' arbitration update (above) is the one dated development in this category this scan, already captured as DEDUPLICATED/read.

## Source coverage

| Source | Status | Detail |
|---|---|---|
| ASX todayAnns listing | OK | curl, 411 rows, 7:30am–12:41pm, not truncated |
| ASX per-company listing | OK | TTT/JNS/DGR/AXL/CAY, all HTTP 200 |
| ASX header API (mkt cap) | OK for TTT/JNS/DGR/AXL; `marketCap:0` for CAY → Not verified (Cat B) |
| ASX documents | OK — see table below |
| TradingView screener | OK — 2 calls, 7+8 rows, neither truncated; `market_cap_basic` blocked for all AU rows per tool hint |
| TradingView news/other tools | Not used — PDF reads covered all catalysts within the 15-doc budget |
| Web search (non-ASX-native) | OK — see section above |
| Company IR / mirrors | Not needed — all docs resolved via ASX pdfURL ladder |

**Documents: 15 attempted / 15 downloaded / 15 extracted / 15 used.**

| Ticker (idsId) | HTTP | Bytes | Chars | Used |
|---|---|---|---|---|
| TTT (03170890) | 200 | 94,190 | 7,212 | Y |
| JNS (03171029) | 200 | 319,014 | 6,122 | Y |
| DGR (03170966) | 200 | 259,785 | 32,270 | Y |
| AXL (03170901) | 200 | 3,721,674 | 165,061 | Y |
| CAY (03170850) | 200 | 1,362,790 | 65,050 | Y |
| SNS (03171155) | 200 | 366,110 | 6,606 | Y |
| GOW (03171120) | 200 | 282,532 | 1,095 | Y |
| EGY (03171132) | 200 | 128,395 | 11,740 | Y |
| MXI (03171106) | 200 | 191,357 | 5,484 | Y |
| VML (03171136) | 200 | 254,385 | 9,268 | Y |
| BPG (03171014) | 200 | 85,178 | 808 | Y |
| SWT (03171020) | 200 | 233,965 | 6,443 | Y |
| AMK (03171048) | 200 | 2,185,310 | 15,489 | Y |
| SRR (03171077) | 200 | 551,385 | 9,624 | Y |
| SMX (03171034) | 200 | 233,007 | 22,100 | Y |

pdfURLs: all under `announcements.asx.com.au/asxpdf/20261126/pdf/`.

Gaps: ADA's -85.47% not researched (sub-$100k TV). NEU/RCM halts still undisclosed. CAY market cap unresolved (header returned clean `0`, not an error, so no retry triggered).

Tools called outside Bash/Read/Write/Edit/Glob/Grep/WebFetch/WebSearch/ToolSearch and the TradingView read tools (run-screener, get-screener-columns): **none.**
