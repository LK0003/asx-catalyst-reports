# ASX SWEEP — Wednesday, 25 November 2026, 12:49pm AEDT (Melbourne)

*Research/screening tool only — not financial advice. Not a recommendation to buy, sell, enter or short anything.*

**Previous report:** `reports/2026-11-25/1015_sweep.md`. Its own header stated its window as "~9:35am–10:12am" (approximate, as written in that file) — treated here as **W = 10:12am**, flagged approximate at source.
**This run's overlap check:** ASX listing re-checked from W−45min (9:27am) through current scan (12:44pm).
**Screener data timestamp:** ~12:44–12:45pm AEDT. `update_mode` = `streaming` for all rows (TradingView).
**Relative volume field:** `relative_volume_10d_calc` — TradingView relative volume, methodology unverified. Do not read as time-adjusted or as a full-day ratio.
**Liquidity rule:** traded value (close×volume, A$) ≥ $100,000 AND market cap ≥ $5m.
**Reconciliation:** Screener rows: gainers 9 + losers 7 = 16; A 4 + B 0 + C 11 + D 0 + E 1 = 16.

## Category A — CONFIRMED LIQUID (traded value ≥$100k, market cap verified ≥$5m, no conflict)

| Ticker | Company | Chg | Rel.vol (unverified methodology) | Traded value (A$) | Mkt cap (ASX header) | Catalyst | Listing time | LISTING/CONTENT | Key risk |
|---|---|---|---|---|---|---|---|---|---|
| WEB | WebBeds Group | −22.8% (screener) / −22.5% (ASX header) | 3.66 | $20,067,655 | $1,221,692,556 | 1H27 result: underlying EBITDA +23% on like-for-like, "exceeding guidance" headline — but statutory NPAT swings to a **$(10.8)m loss** on a **$7m 1H27 + $50m one-off provision for a Spanish tax matter (STM)**. Negative surprise despite positive-sounding headline. | 8:17am | LISTING verified (today's listing, idsId 03170116/03170114); CONTENT read — pdftotext of both PDFs, text extracted (24,418 and 149,623 chars), figures above quoted directly. Source: asx.com.au → announcements.asx.com.au pdfURL. | STM liability could grow; FX headwind (~9% AUD/EUR) persists; statutory loss optics. |
| TYR | Tyro Payments | +17.4% (screener) / +15.2% (ASX header) | 2.73 | $367,913,460 | $40m on-market buy-back approved (APRA-approved, ≤10% of issued capital/12mo) announced alongside FY27 guidance reaffirmation ($240–255m gross profit, 28.5–30.5% EBITDA margin) at today's AGM. | 8:27am (buy-back); 8:44am (AGM/guidance) | LISTING verified (idsId 03170175, 03170208); CONTENT read — pdftotext extracted 3,616 and 39,876 chars; buy-back terms and guidance figures quoted directly from text. | Buy-back size/timing discretionary; recently appointed interim CFO (24 Nov); guidance merely reaffirmed, not raised. |
| PTX | Prescient Therapeutics | −62.7% (screener) / −63.6% (ASX header) | 97.3 | $62,911,748 | Phase 2a PTX-100 (CTCL) Dose Optimisation Committee review: "modest efficacy," 6/20 evaluable patients had disease progression, **DOC found data insufficient to select a dose**, recommended enrolment continue; company to review program. | 8:58am | LISTING verified (idsId 03170237); CONTENT read — pdftotext extracted 11,818 chars, figures quoted directly. | Dose-finding unresolved; program-level strategic review pending; early-stage biotech cash-runway risk. |
| UNT | Unith | −33.3% (screener and ASX header, exact match) | 17.97 | $11,073,062 | Binding deal to acquire 100% of Netherlands-based ServiceHighway ("scale-up" framing) funded via **Appendix 3B proposing up to 2,883,064,516 new ordinary shares** (+1.21bn performance rights) — severe dilution relative to an $11m market cap. | 9:39am (deal); 9:41am (Appx 3B) | LISTING verified (idsId 03170309, 03170315); CONTENT read — pdftotext extracted 68,235 and 12,679 chars; share-count figures quoted directly. | Dilution scale vs pro-forma A$8.13m revenue; cross-border integration; FY2025 ServiceHighway EBITDA only ~A$1.4m. |

## Category B — CAP NOT VERIFIED
None this scan (all traded-value≥$100k rows resolved a market cap via the ASX header API).

## Category E — DATA CONFLICT (listed separately, never counted as confirmed)
| Ticker | Screener | ASX header | Conflict | Halt check |
|---|---|---|---|---|
| KAL | change −15.38%, volume 79,230,288 | change 0%, volume 0 | Header shows zero volume/zero change vs active screener trade — >5pp and volume discrepancy | KAL per-company listing (past wk) shows only one filing today, 8:19am, "RC and Aircore programs completed at Pinjin," **not price-sensitive**, no halt/suspension notice found. Conflict unresolved — likely a stale/cached ASX-header read, not a confirmed halt. |

## Categories C and D (counts + top-5 by traded value; market cap not required)
- **C (traded value <$100k):** 11 rows. Top 5: COB $75,390 (+15.3%), DYM $71,210 (−21.8%), CP8 $49,137 (+20.8%), ADD $46,033 (+16.0%), IMA $43,096 (+15.8%).
- **D (traded value ≥$100k, verified cap <$5m):** 0 rows.

## Overlap evidence (price-sensitive announcements, W−45min [9:27am] → 12:44pm scan)
39 price-sensitive rows retrieved in window; 136 non-price-sensitive rows in the same window are **not individually assessed** (count only). T = listing time; W = 10:12am.

| Time (T) | Ticker | Title | idsId | Grep result | Classification |
|---|---|---|---|---|---|
| 9:33am | ART | FY26 AGM Chair Address | 03170297 | no match | MISSED BY EARLIER REPORT |
| 9:34am | MGH | Suspension from Quotation | 03170300 | 0939_full.md:138–153,239,303,348 | DEDUPLICATED |
| 9:35am | ART | FY26 AGM Presentation | 03170302 | no match | MISSED BY EARLIER REPORT |
| 9:36am | ARD | Further High-Grade Gold Intersected at Trunkey Creek | 03170304 | 1015_sweep.md:35 | DEDUPLICATED |
| 9:36am | GNG | FY26 AGM Presentation | 03170303 | no match | MISSED BY EARLIER REPORT |
| 9:38am | CU6 | Chair's Address to Shareholders | 03170308 | no match | MISSED BY EARLIER REPORT |
| 9:38am | FRS | Ore Purchase Agreement Secured with Javelin Minerals | 03170305 | 1015_sweep.md:36 | DEDUPLICATED |
| 9:39am | UNT | UNT enters scale-up phase with acquisition of ServiceHighway | 03170309 | no match | **MISSED BY EARLIER REPORT** (today's largest-TV small-cap mover; see Category A) |
| 9:40am | TUA | Response to ASX Price Query | 03170312 | 1015_sweep.md:29 | DEDUPLICATED |
| 9:40am | MSX | MSX Raises $6M to Fast Track Phase 2 Clinical Trial | 03170311 | 1015_sweep.md:31 | DEDUPLICATED |
| 9:44am | BUS | Skyline Update and Withdrawal from Victorian Gold Option | 03170320 | no match | MISSED BY EARLIER REPORT |
| 9:44am | CQT | Significant Management & Operational Restructuring | 03170319 | 1015_sweep.md:28 | DEDUPLICATED |
| 9:48am | PME | PME Receives FDA Clearance for Visage7 AI Mammography | 03170326 | 1015_sweep.md:27 | DEDUPLICATED |
| 9:51am | CMG | Pause in Trading | 03170334 | 1015_sweep.md:25 | DEDUPLICATED |
| 9:52am | GDR | High Grade Shoot Continues at Depth with 4m @ 7.84 g/t | 03170335 | 1015_sweep.md:34 | DEDUPLICATED |
| 9:55am | EPM | Eclipse Completes Drilling Program at Gronnedal | 03170338 | 1015_sweep.md:33 | DEDUPLICATED |
| 9:55am | JAV | Javelin Executes Ore Purchase Agreement with Forrestania | 03170337 | 1015_sweep.md:36 | DEDUPLICATED |
| 9:56am | BPG | Suspension from Quotation | 03170340 | 1015_sweep.md:24 | DEDUPLICATED |
| 9:57am | ILT | Drilling Demonstrates Material Orient Extension Upside | 03170342 | 1015_sweep.md:32 | DEDUPLICATED |
| 9:58am | L1M | Placement to Advance Mt Turner and Warby Exploration | 03170343 | no match | MISSED BY EARLIER REPORT |
| 10:01am | JNS | Pause in Trading | 03170347 | 1015_sweep.md:26 | DEDUPLICATED |
| 10:05am | PME | PME – AGM 2026 – Presentation | 03170351 | no match (distinct idsId from the FDA item) | MISSED BY EARLIER REPORT |
| 10:05am | VR1 | Vection to enter the USA market with acquisition of zSpace | 03170350 | 1015_sweep.md:30 | DEDUPLICATED |
| 10:09am | EQR | Chair's Address to Shareholders | 03170356 | no match | MISSED BY EARLIER REPORT |
| 10:12am | MA1 | Dividend/Distribution – MA1 | 03170361 | no match | MISSED BY EARLIER REPORT (at-cutoff-minute item, T=W) |
| 10:14am | SYL | 2026 AGM – Chairman and MD Address | 03170363 | — (T>W) | NEW |
| 10:16am | JNS | Trading Halt | 03170365 | — (T>W) | NEW |
| 10:27am | CMB | Corporate Presentation and Phase 3 Timeline Update | 03170375 | — (T>W) | NEW |
| 10:37am | CMG | Trading Halt | 03170382 | — (T>W) | NEW |
| 10:55am | MAP | Appointment of Voluntary Administrators | 03170390 | — (T>W) | NEW |
| 10:57am | HCL | Rifle Armor Plates Delivered to Latin America | 03170392 | — (T>W) | NEW |
| 11:42am | ALM | AGM Presentation | 03170418 | — (T>W) | NEW |
| 11:56am | URF | Dividend/Distribution – URF | 03170429 | — (T>W) | NEW |
| 11:57am | VR1 | Reinstatement to Quotation | 03170432 | — (T>W) | NEW |
| 11:58am | JNS | Janus Electric – Pipeline and Acceleration Presentation | 03170434 | — (T>W) | NEW |
| 12:02pm | HMX | Implementation of the Scheme | 03170436 | — (T>W) | NEW |
| 12:35pm | STN | Chair's Address to Shareholders | 03170459 | — (T>W) | NEW |
| 12:36pm | SRH | Chair's and MD's Address to Shareholders | 03170461 | — (T>W) | NEW |
| 12:42pm | NXG | NexGen Grows High-Grade Subdomain Vertically & Along Strike | 03170466 | — (T>W) | NEW |

Note: UNT's 9:39am acquisition/dilution announcement was not picked up by the 10:15am sweep and is the clearest MISSED item of materiality — it underlies today's confirmed −33.3% mover (Category A above).

## Non-ASX-native catalyst check
Explicit search run this scan (WebSearch) for US federal court/agency action affecting ASX-listed critical-minerals/resource names. No result dated 25 Nov 2026 found. Closest matches: Dateline Resources' Colosseum injunction (DOJ stay motion, date unclear from search) and ioneer's Rhyolite Ridge court win (dated March 2026 per source, not today). One ASX ticker surfaced — USC — but its only announcement in the past week is today's non-price-sensitive "Results of Meeting" (11:35am); the "US REE Project federal court proceedings" item found by web search is not in USC's past-week ASX listing, so it is **not today's news** and not used as a catalyst here.

## Source coverage
| Source | Status | Detail |
|---|---|---|
| ASX today's-listing (todayAnns.do) | OK | 390 rows, 7:30am–12:42pm, via curl (single fetch, no pagination markers found — listing appears complete to scan time) |
| ASX per-company listing (announcements.do) | OK | Fetched for KAL, WEB, TYR, PTX, UNT, USC (period=W) |
| ASX header API (markitdigital) | OK | Fetched for WEB, TYR, KAL, PTX, UNT — all 200 |
| ASX documents (PDF) | OK | 7/7 downloaded (200, bytes confirmed), 7/7 text-extracted (pdftotext exit 0), 7/7 used — see table below |
| TradingView screener | OK | Two calls (gainers ≥15%/relvol≥2, losers ≤−15%/relvol≥2); market_cap_basic blocked for AU (expected, per tool hint) |
| TradingView news/get-news | Not called | Primary ASX documents were sufficient and read directly; not needed for the 4 Category-A names |
| Web search (non-ASX-native catalysts) | OK | One search run; no today-dated US federal court/agency catalyst found for ASX names |

**Document table (downloaded / text-extracted / used):**
| idsId | Ticker | pdfURL | HTTP | Bytes | Extracted chars | Used? |
|---|---|---|---|---|---|---|
| 03170114 | WEB | .../0770r8fcwgzvyk.pdf | 200 | 3,424,300 | 149,623 | Yes |
| 03170116 | WEB | .../0770rdplhnzlyg.pdf | 200 | 324,956 | 24,418 | Yes |
| 03170175 | TYR | .../0770wh3p096cxj.pdf | 200 | 172,365 | 3,616 | Yes |
| 03170208 | TYR | .../0770yvgbsk00fw.pdf | 200 | 12,487,832 | 39,876 | Yes |
| 03170237 | PTX | .../07710xpxr852qy.pdf | 200 | 338,463 | 11,818 | Yes |
| 03170309 | UNT | .../077163bgy0z0d3.pdf | 200 | 1,980,744 | 68,235 | Yes |
| 03170315 | UNT | .../07716jd9h2clp0.pdf | 200 | 16,916 | 12,679 | Yes |

**Tools called outside Bash/Read/Write/Edit/Glob/Grep/WebFetch/WebSearch/ToolSearch and the TradingView read tools (run-screener, get-screener-columns):** none.

---
*Research/screening tool only. Not financial advice.*
