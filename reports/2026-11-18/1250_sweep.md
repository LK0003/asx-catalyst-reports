# ASX Catalyst Sweep — 18 November 2026, 12:50pm AEDT

**Previous report / cutoff used:** `reports/2026-11-18/1016_sweep.md` (actual window checked: ~09:35am–10:14am; scan ~10:16am) — this sweep's overlap window is ~09:30am–12:44pm.
**Data timestamp:** TradingView screener queried 12:44pm AEDT; all rows `update_mode: streaming`.
**Volume basis:** `relative_volume_10d_calc` = today's cumulative volume ÷ a FULL-DAY 10-day average volume. At 12:44pm (~70% through the 10am–4pm session) this still understates full-day relative volume for all rows below.
**Liquidity threshold:** traded value (close × volume, A$) ≥ $100,000 AND market cap ≥ $5m.
**Reconciliation:** Screener rows: gainers 12 + losers 10 = 22; liquid 4 + illiquid 18 = 22; illiquid gainers 8 + illiquid losers 10 = 18.

This is a research/screening tool, not financial advice. Nothing here is a recommendation to buy, sell, or hold any security.

---

## Liquid movers (traded value ≥ A$100k, mkt cap ≥ A$5m)

| Ticker | Company | Chg | Rel.vol (10d avg basis) | Traded value | Catalyst | Listing time | Flags / source | Key risk |
|---|---|---|---|---|---|---|---|---|
| NXL | Nuix | +45.3% (screener close $2.31; ASX live feed $2.34, +47.2%) | 2.98x | ~A$8.65m | **Verified.** Nuix entered a Process Deed with Haveli Investments on an unsolicited, non-binding, indicative $2.75/share cash proposal (73% premium to 17 Nov close). Follows earlier lower Haveli proposals since Jul 2026. | 8:48am | LISTING verified (today's listing, idsId 03167026); CONTENT read — pdfURL `announcements.asx.com.au/asxpdf/20261118/pdf/076qnbl5y41grt.pdf` | Non-binding; conditional on DD, exclusivity, unanimous board rec, binding SID, regulatory & shareholder approval — real deal-completion risk |
| GG8 | Gorilla Gold Mines | +43.4% (close $0.38) | 8.90x | ~A$3.51m | **Verified.** Tembo Capital-cornerstoned A$60m placement (firm commitments) to fund the already-disclosed Cosmos acquisition from IGO; priced at last close + 6% premium to 10-day VWAP. Pro-forma cash ~A$69.5m. | 9:20–9:21am | LISTING verified; CONTENT read — pdfURL `.../076qscn0r4dz5x.pdf` | Materiality largely carried forward from 0936_full.md (binding SPA already known); this confirms raise completed, not new resource/production news |
| BUY | Bounty Oil & Gas | +60% (close $0.008) | 10.54x | ~A$213.3k | **Verified.** Initial interpretation of licensed TGS Sunfish 3D seismic over Liberia Block LB-32 identifies 4 exploration leads (stacked Upper Cretaceous turbidite plays, amplitude anomalies) — early-stage, pre-drill. | 9:08am | LISTING verified; CONTENT read — pdfURL `.../076qqxt0l9l5pf.pdf` | Leads only — no drilling yet; sub-cent stock, extreme volatility; PSC progression still required |
| RMX | Red Mountain Mining | Screener shows +20% (close $0.012), vol 26.7m, rel.vol 26.7x | — | n/a — **see flag** | **Not a genuine mover this run.** ASX's own live header shows volume=0, change=0% today. RMX has been in a trading halt since 17 Nov 9:51am (pending an announcement), due to resume by the earlier of the announcement or normal trading Thu 19 Nov. The TradingView screener figures for RMX appear to be a stale pre-halt snapshot, not today's session. | No row in today's listing | LISTING: no matching announcement found in today's listing (342 rows retrieved, 7:30am–12:42pm); per-company listing shows halt notice 17/11 9:51am; CONTENT read (halt notice PDF, `.../076p7x9m3j325d.pdf`) | Screener data-quality gap — treat RMX's "mover" status as unverified/stale, not as a live reaction |

## Illiquid movers

18 of 22 screened rows are illiquid (traded value < $100k): 8 gainers, 10 losers. Top 5 by traded value (descending):
RLG −20% (TV ~A$60.4k) · GAS −28.6% (TV ~A$37.7k) · AXI +25% (TV ~A$35.9k) · EVE −15.4% (TV ~A$31.6k) · SRN +25% (TV ~A$29.5k)

## Overlap evidence (window ~09:30am–12:44pm, dedup vs `0936_full.md` and `1016_sweep.md`)

| Ticker | Listing time | Title | Price-sens. | Grep result | Classification |
|---|---|---|---|---|---|
| GML | 9:34am | Yandal Project Exploration Update | Y | no match in 0936_full.md or 1016_sweep.md | **MISSED by earlier report** |
| LGM | 9:32am | 3km Copper-Gold System defined in Drilling Fontenoy | Y | no match in 0936_full.md or 1016_sweep.md | **MISSED by earlier report** |
| GSS/MAP | 9:57–9:58am | End of Proposed Merger with Microba | Y | 1016_sweep.md:22 (flagged, reason unread) | DEDUPLICATED — this run adds the reason (GSS doc, idsId 03167127): Microba notified it lacks financial capacity to complete without additional capital |
| EQU | 9:46am | 1.56 Tcf (2U) Near-Field Prospective Gas | Y | 1016_sweep.md:23 | DEDUPLICATED — primary doc (idsId 03167114) confirms 1.56 Tcf is additional 2U prospective-category upside, not a restatement of the existing 1.7 Tcf 2C contingent resource |
| EML | 10:01am | Q1 FY27 Trading Update | Y | 1016_sweep.md:24 | DEDUPLICATED — primary doc (idsId 03167135) shows FY27 EBITDA guidance **affirmed** at $50–54m (in-line, not a beat); stock down ~13% today — consistent with a neutral/non-beat read despite a "reaffirm" headline |
| GAS/POW/DUN/ODY/VKA | 9:46–9:52am | Exploration/EOI updates | Y | 1016_sweep.md:26 | DEDUPLICATED |
| VEN | 11:34am | Refinancing & Southern Flank JV restructuring | Y | no match | NEW — up to $12m 20-yr SA Govt loan (subject to agreement) + JV restructuring; stock shown down ~25% intraday per TradingView live quote (not a liquid-mover per our screen) |
| LIO | 12:03pm, 12:16pm | Pause in Trading / Trading Halt | Y | no match | NEW — halt pending an announcement, resumes by Fri 20 Nov or on release |
| EPX, HAV, WMG, SVR, AVG, AUI, SFC, BH6, YOW | 10:26am–12:42pm | AGM addresses, capital raise, drilling update, dividend, IPO | mixed | no match | NEW — lodged after 1016's cutoff; not individually read this run (routine/sub-threshold by headline) |
| NXL | 8:48am | Process Deed w/ Haveli | Y | 0936_full.md:25 | DEDUPLICATED (predates window; already covered as top candidate) |
| BUY | 9:08am | LB-32 seismic | Y | 0936_full.md:136 (listed, not materiality-assessed) | DEDUPLICATED — upgraded from headline-only to read/assessed this run |

**Non-ASX-native catalyst check:** Web search for US federal court/DOJ/DOE/foreign-regulatory action touching ASX critical-minerals names (18 Nov 2026) found nothing dated today; Dateline Resources' (DTR) Ninth Circuit Colosseum appeal status unchanged since the last report — no new ruling found.

**Historical overlap test:** see `reports/2026-11-18/1250_overlap_test.md` (test mode, triggered because today's Melbourne date is 2026-11-18) — result: **PASS**.

## Source coverage

| Source | Status | Notes |
|---|---|---|
| ASX `todayAnns.do` | OK | 342 rows, 7:30am–12:42pm, via curl |
| ASX per-company listing (NXL/GG8/BUY/RMX/VEN/LIO) | OK | via curl |
| ASX documents (`displayAnnouncement.do` → pdfURL → PDF) | OK | 10/10 attempted docs retrieved, text extracted via `pdftotext -layout` for all 10 |
| TradingView screener | OK | streaming feed |
| TradingView get-news (NXL, GG8) | OK | secondary confirmation only |
| TradingView get-symbol-data-batch (market cap) | Partial | `market_cap_basic` blocked ("cannot be offered within TradingView" for AU); substituted ASX header API (`asx.api.markitdigital.com`) for the 4 liquid candidates |
| Web search — non-ASX-native catalysts | OK | no new findings |

Tools called outside Bash/Read/Write/Edit/Glob/Grep/WebFetch/WebSearch and the TradingView read-only research tools (run-screener, get-screener-columns, get-symbol-data, get-symbol-data-batch, get-news, get-news-story, search-symbols): **none**.

---
*Research/screening tool only. This report does not constitute financial advice and contains no recommendation to buy, sell, or hold any security.*
