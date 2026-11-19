# ASX SWEEP — Thursday 19 November 2026, scan ~12:49pm AEDT (Melbourne)

Research/screening tool, not financial advice. Nothing here is a recommendation to buy, sell, or hold.

Previous report: `reports/2026-11-19/1016_sweep.md`, stated window end **W = 10:16am** AEDT (its own scan-time statement, not the scheduled slot). Overlap re-checked from W−45min (9:31am) through this scan (12:45pm-ish, last listing row 12:38pm).

TradingView screener data timestamp: run at this scan, `update_mode: streaming` (live/intraday feed, not end-of-day). **TradingView relative volume — methodology unverified** (field `relative_volume_10d_calc`; not documented precisely for stocks, not described here as time-adjusted or as over/understating intraday volume).

Liquidity rule: traded value (close×volume) ≥ A$100,000 **and** market cap ≥ A$5m = CONFIRMED LIQUID (A).

**Reconciliation:** Screener rows: gainers 12 + losers 5 = 17; A 2 + B 1 + C 14 + D 0 + E 0 = 17.

---

## Category A — CONFIRMED LIQUID

| Ticker | Company | Change | Rel.vol (unverified) | Traded value | Market cap (ASX header) | Catalyst | Listing time | LISTING/CONTENT | Key risk |
|---|---|---|---|---|---|---|---|---|---|
| MHK | Metal Hawk | +25.0% (screener) / +26.9% (ASX hdr) | 38.4x | A$832,097 | A$17.6m | **Verified**: "11m @ 48.3g/t Au Confirms New Discovery at the Numbat Shear" — RC drilling incl. 6m@81.2g/t Au, 4m@28.5g/t Au, 27m@5.7g/t Au; highest-grade intersections at Leinster South to date; diamond drilling underway/program expanding | 9:22am | LISTING verified (idsId 03167699, seen in ASX per-company listing); CONTENT read — pdfURL https://announcements.asx.com.au/asxpdf/20261119/pdf/076sgmdjppyn9s.pdf | Downhole lengths only, true widths not yet known; single-hole bonanza intercepts can overstate continuity |
| PRB | Parbo Resources | +29.6% (screener) / +33.3% (ASX hdr) | 13.0x | A$132,682 | A$17.3m | **Verified, but assay-pending**: "Parbo Discovers New Greenstone Belt at Mount Padbury" — greenstone intersected from 44m depth at GoldenEye beneath granite; sulphide-bearing breccia at Goldfinger; analogised to producing Plutonic mine (CYL) on same structure; **all results visual/geophysical — assays pending, expected Q1 2027** | 9:36am | LISTING verified (idsId 03167723); CONTENT read — pdfURL https://announcements.asx.com.au/asxpdf/20261119/pdf/076sjc0jtl21dw.pdf | Explicit company caution: visual estimates are not a proxy for lab assay grade; could reverse if assays disappoint |

## Category B — CAP NOT VERIFIED (never merged into A)

| Ticker | Company | Change | Rel.vol (unverified) | Traded value | Market cap | Catalyst | Listing time | LISTING/CONTENT |
|---|---|---|---|---|---|---|---|---|
| ACW | Actinogen Medical | −77.8% | 20.6x | A$1,537,724 | **Not verified** — ASX header API returned `marketCap: 0` for an actively-traded stock (likely a data gap, not a true value); priceChangePercent (−77.78%) and volume matched screener, so not reclassified as E | **Verified — negative surprise despite "trend toward benefit" framing**: pivotal XanaMIA Alzheimer's trial of Xanamem — primary endpoint (CDR-SB disease progression, overall population) was **numerically but NOT statistically significant** vs placebo (p=0.65); only a prespecified older-patient subgroup and a secondary "zero-progression rate" measure hit significance; company still well-funded ($18.9m cash to CY2028). Independent corroboration: Quartr news summary headlines "Xanamem missed the overall endpoint." This is a bona fide pivotal-trial primary-endpoint miss, not routine news — explains the halt→suspension→drop sequence | Reinstated 9:40am; underlying trial-results doc lodged 8:32am | LISTING verified (idsId 03167608); CONTENT read — pdfURL https://announcements.asx.com.au/asxpdf/20261119/pdf/076s82q9dnvg97.pdf |

## Category E — none this run.

## Category C (traded value < A$100k): 14 rows. Top 5 by traded value: RLG (−20.0%, A$60,403), HOR (+28.6%, A$37,618), AXI (+25.0%, A$35,861), HYT (+19.2%, A$27,598), RGL (+16.7%, A$23,343).
## Category D (cap verified < A$5m): 0 rows.

---

## Overlap — price-sensitive announcements, W−45min (9:31am) to scan (last row 12:38pm)

239 total listing rows in window; **51 price-sensitive** (non-PS rows: 188, not individually assessed). Grep run against `0816_sweep.md`, `0935_full.md`, `1016_sweep.md`.

| Time | Ticker | idsId | Title (short) | Grep result | Classification |
|---|---|---|---|---|---|
| 9:31am | LIO | 03167712 | Bula Karang-1 oil update | no match | MISSED BY EARLIER REPORT |
| 9:31am | VR1 | 03167711 | Trading Halt | 0935_full.md:155 | DEDUPLICATED |
| 9:32am | WC1 | 03167716 | Suspension from Quotation | 0935_full.md:158 | DEDUPLICATED |
| 9:32am | UBN | 03167713 | Urbanise/PICA partnership | no match | MISSED BY EARLIER REPORT |
| 9:34am | LIC | 03167720 | Chair/CEO AGM Presentation | no match | MISSED BY EARLIER REPORT |
| 9:34am | VKA | 03167719 | Scheelite logged, 11 more holes | 0935_full.md:139,197 | DEDUPLICATED |
| 9:36am | PIM | 03167727 | US tungsten drilling, Mar-27 Q | 1016_sweep.md:37 | DEDUPLICATED |
| 9:36am | AS1 | 03167725 | Binding term sheet, Siguiri Gold | 1016_sweep.md:30 | DEDUPLICATED |
| 9:36am | PRB | 03167723 | New greenstone belt, Mt Padbury | no match | MISSED BY EARLIER REPORT (now covered above, Cat. A) |
| 9:37am | NHC | 03167730 | Dividend/Distribution | no match | MISSED BY EARLIER REPORT |
| 9:37am | FTI | 03167728 | FortifAI appoints ex-Nvidia CEO | 1016_sweep.md:35 | DEDUPLICATED |
| 9:38am | RMX | 03167732 | Funding, Armidale project | 1016_sweep.md:32 | DEDUPLICATED |
| 9:40am | NHC | 03167738 | Dividend announcement | no match | MISSED BY EARLIER REPORT |
| 9:40am | ACW | 03167737 | Reinstatement to Quotation | 1016_sweep.md:40 | DEDUPLICATED |
| 9:45am | HRN | 03167746 | MD's AGM Presentation | no match | MISSED BY EARLIER REPORT |
| 9:47am | 1TT | 03167750 | Updated Appendix 4C | no match | MISSED BY EARLIER REPORT |
| 9:51am | ATV | 03167755 | Pause in Trading | 1016_sweep.md:39 | DEDUPLICATED |
| 9:53am | IVR | 03167759 | Response to ASX Volume Query | 1016_sweep.md:38 | DEDUPLICATED |
| 9:56am | ARD | 03167767 | $1.55M Placement, Kempfield | no match | MISSED BY EARLIER REPORT |
| 9:58am | TIO | 03167772 | Quebec RCL contract signed | 1016_sweep.md:33 | DEDUPLICATED |
| 9:58am | EDE | 03167771 | EdenCrete demand update Q2 FY27 | no match | MISSED BY EARLIER REPORT |
| 9:59am | SCN | 03167773 | Paynes Find acquisition | 1016_sweep.md:31 | DEDUPLICATED |
| 10:02am | EIQ | 03167777 | Pause in Trading | 1016_sweep.md:39 | DEDUPLICATED |
| 10:03am | BH6 | 03167780 | Notice of General Meeting (588pg) | no match | MISSED BY EARLIER REPORT |
| 10:04am | GDM | 03167783 | Oct monthly production update | 1016_sweep.md:34 | DEDUPLICATED |
| 10:05am | NRE | 03167785 | Pause in Trading | 1016_sweep.md:39 | DEDUPLICATED |
| 10:05am | ACQ | 03167784 | 2026 AGM Presentation | no match | MISSED BY EARLIER REPORT |
| 10:07am | G88 | 03167787 | Private Placement $950,000 | no match | MISSED BY EARLIER REPORT |
| 10:15am | FEL | 03167793 | JV w/ 88 Energy, Kad River East | no match | MISSED BY EARLIER REPORT |
| 10:15am | 88E | 03167793 | FEL: JV, Kad River East | no match | MISSED BY EARLIER REPORT |
| 10:16am | FEL | 03167794 | Agrees expanded JV, Kad River East | no match | MISSED BY EARLIER REPORT (at-cutoff-minute, T=W) |
| 10:16am | 88E | 03167794 | Agrees expanded JV, Kad River East | no match | MISSED BY EARLIER REPORT (at-cutoff-minute, T=W) |
| 10:20am | EIQ | 03167797 | Trading Halt | — | NEW |
| 10:23am | ATV | 03167798 | Trading Halt | — | NEW |
| 10:27am | DAL | 03167800 | Diamond drilling begins, Bondoukou | — | NEW |
| 10:33am | HMY | 03167806 | 2026 AGM Chair/CEO addresses | — | NEW |
| 10:36am | APL | 03167807 | 2026 AGM Chair's address | — | NEW |
| 10:41am | APL | 03167810 | 2026 AGM investor presentation | — | NEW |
| 10:42am | RNV | 03167811 | Release of securities from escrow | — | NEW |
| 10:44am | SSG | 03167813 | Trading update | — | NEW |
| 10:46am | SSG | 03167815 | AGM Chair/CEO address | — | NEW |
| 10:47am | SSG | 03167816 | 2026 AGM Presentation | — | NEW |
| 11:10am | BB1 | 03167829 | $1.22M R&D tax incentive refund | — | NEW |
| 11:10am | SPN | 03167828 | Leadership transition | — | NEW |
| 11:31am | PLY | 03167844 | Chairman/CEO AGM addresses | — | NEW |
| 11:36am | NRE | 03167845 | Suspension from Quotation | — | NEW |
| 11:37am | PLY | 03167847 | AGM Presentation | — | NEW |
| 11:44am | CYB | 03167853 | Chair's Address to Shareholders | — | NEW |
| 11:46am | CYB | 03167859 | Investor Presentation | — | NEW |
| 11:51am | OML | 03167863 | Scheme Effective & dividend determined | — | NEW |
| 12:17pm | AMN | 03167874 | AGM Presentation | — | NEW |

None of the MISSED or NEW items above were individually re-verified against their underlying PDFs this run beyond PRB (already read, see Cat. A/B). Most AGM chair/CEO-address and presentation items in the NEW set are routine AGM-season disclosures, not independently assessed for materiality beyond their headline.

**Non-ASX-native catalyst check:** web search run this scan for US court/DOJ/DOE/DOD/FDA/SEC or other offshore action tied to ASX-listed resource names. No November 19, 2026-dated development found; most relevant hit (Rhyolite Ridge/ioneer federal court permit upholding) is dated March 2026, not today. No new development on the standing DTR/USC rare-earths litigation thread.

---

## Source coverage

| Source | Status | Notes |
|---|---|---|
| ASX todayAnns listing | OK | curl, 449 rows, 7:30am–12:38pm, no pagination control found — treated as complete single-day page |
| ASX per-company listing (ACW/MHK/PRB) | OK | curl, D/W timeframe, exact times/PS flags/idsIds obtained |
| ASX header API (market cap) | OK (ACW partial) | MHK $17.6m, PRB $17.3m confirmed; ACW returned `marketCap:0` — treated as not verified, not as a true zero |
| ASX documents | OK | 3/3 downloaded, 3/3 text-extracted, 3/3 used (table below) |
| TradingView screener | OK | gainers 12/12 (not truncated), losers 5/5 (not truncated); `market_cap_basic` blocked by TradingView for AU stocks (per API hint) |
| TradingView get-news | OK | ACW only — corroborated "missed overall endpoint" framing |
| Web search (non-ASX-native check) | OK | no Nov-19-dated hit |

**Documents:** idsId | ticker | pdfURL | HTTP | bytes | extracted chars | used
03167608 | ACW | .../076s82q9dnvg97.pdf | 200 | 1,165,449 | 42,650 | yes
03167699 | MHK | .../076sgmdjppyn9s.pdf | 200 | 2,735,025 | 73,875 | yes
03167723 | PRB | .../076sjc0jtl21dw.pdf | 200 | 1,973,494 | 67,385 | yes

No gaps beyond: ACW market cap not verified; MISSED/NEW overlap items beyond PRB not individually re-verified against their PDFs this run (time budget).

Tools called outside Bash/Read/Write/Edit/Glob/Grep/WebFetch/WebSearch/ToolSearch and the TradingView read tools: none.
