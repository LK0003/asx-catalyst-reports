# ASX EVENING SWEEP — Delta Scan

**Date:** Tuesday, 17 November 2026
**Scan time:** ~19:22 AEDT (Melbourne)
**Previous report / cutoff used:** `1907_sweep.md`, stated window "~16:53–19:00 AEDT" → cutoff **19:00 AEDT**
**Overlap window checked:** ~18:15–19:22 AEDT (cutoff minus 45 min through now), via `asx.com.au/asx/v2/statistics/todayAnns.do` (directly accessible this run)
**Data timestamp / feed status:** ASX cash market closed at 16:00 AEDT (~3h20m before this scan). TradingView screener rows below are today's **closing-session** change/volume figures — `update_mode` shows `"streaming"` (TradingView's symbol classification) but no new trades have occurred since the 16:10ish closing auction, so these figures are unchanged from the `1653_sweep.md` / `1907_sweep.md` data.
**Volume basis:** `relative_volume_10d_calc` = today's (closing) cumulative volume ÷ a full-day 10-day average volume — not understated tonight since the session is fully closed.
**Liquidity threshold:** a mover is LIQUID only if traded value (close × volume, A$) ≥ A$100,000 **and** market cap ≥ A$5m.
**Historical overlap test:** see separate file `1922_overlap_test.md` (date-coincidental test-mode run per standing instructions; not current research).

This is a research/screening tool, not financial advice. Nothing here is a recommendation to buy, sell, or hold any security.

---

## 1. Liquid movers (±15%+, rel. vol ≥2x) — unchanged from `1653_sweep.md`

No new trades have occurred since market close, so tonight's screen returns the identical closing-price set already fully verified in `1653_sweep.md`. Summary (full verification detail, sources and "unexplained" research in that file):

| Ticker | Company | Change | Rel. vol | Traded value | Catalyst | LISTING/CONTENT |
|---|---|---|---|---|---|---|
| MYX | Mayne Pharma | +87.2% | 11.1x | ~$35.2m | Gedeon Richter A$6.40/sh cash scheme | Verified / read (`0936_full.md`) |
| IOV | Ion Video | +20.1% | 11.6x | ~$959k | AWS-funded PoC results + price-query response | Verified / read |
| BKT | Black Rock Mining | +66.7% | 10.5x | ~$127k | US$5m working-capital draw-down | Partially verified / headline |
| RMX | Red Mountain Mining | +20.0% | 26.7x | ~$321k | Capital-raising halt (resumed, outcome unconfirmed) | Partially verified / headline |
| STP | Step One Clothing | +15.4% | 18.9x | ~$186k | **UNEXPLAINED — RESEARCH REQUIRED** (reconfirmed this run, no ASX item at all today) | Not verified |
| EGR | EcoGraf | +15.8% | 4.1x | ~$105k | **UNEXPLAINED — RESEARCH REQUIRED** (reconfirmed) | Not verified |
| INN | Innovaero Technologies | -21.4% | 3.2x | ~$148k | **UNEXPLAINED — RESEARCH REQUIRED** (reconfirmed) | Not verified |
| SKK | Stakk Ltd | -18.75% | 12.4x | ~$1.64m | **UNEXPLAINED — RESEARCH REQUIRED** (reconfirmed; largest unexplained traded value) | Not verified |
| RML | Resolution Minerals | -15.6% | 2.7x | ~$372k | **UNEXPLAINED — RESEARCH REQUIRED** (reconfirmed; plausible sector-beta inference only) | Not verified |
| CAT | Catapult Sports | -16.6% | 4.7x | ~$18.2m | 1H FY27 result sold off despite +66% earnings | Verified / read |

Re-checked ASX's full today's-announcements listing (both halves of the page) this run specifically for STP/EGR/INN/SKK/RML tickers: **zero matches at any time today** — confirms these five remain genuinely unexplained from the announcements feed, not a search gap.

## 2. Illiquid movers (did not meet A$100k value / A$5m cap threshold)

22 illiquid movers found (14 gainers, 8 losers would be inverted — actual: 8 illiquid gainers, 14 illiquid losers), all unchanged from `1653_sweep.md`'s closing data. Top 5 by traded value: MMR (+100%, ~$1.9k), RAD (-25%, ~$65k), RLG (-20%, ~$60k), ASH (-21.4%, ~$81k), AXI (+25%, ~$36k).

## 3. New / missed announcements — overlap window (18:15–19:22)

Items 18:15–19:00 (MNC, NGX, MI6, KAT, AON, FFI, WGR, GBM, PLA, WAG, DDR, EMR, GNC, CCP, CKF, CWY, AOV, IFG, PIL — all non-price-sensitive routine AGM/holder/director notices) were cross-checked by ticker against `1907_sweep.md`'s routine-item summary — **all already covered, no misses**.

New since the 19:00 cutoff:

| Ticker | Time | Headline | Price-sensitive | Take | Flags / source |
|---|---|---|---|---|---|
| **LFT** | 7:21pm | Summer Drilling Results, Adina Lithium Project, Québec | **Y** | Material-looking exploration update: GlobeNewswire/TradingView headline cites 45m @ 2.71% Li₂O — a strong intercept if confirmed at width/true-depth, but full assay table and context (hole location, program completion %) not independently read. Too late for today's session; relevant to tomorrow's open. | LISTING verified (ASX feed) / CONTENT read from GlobeNewswire news story (headline figures only, not full ASX PDF) |
| **VAU** | 7:03pm | Suspension from Quotation | **Y** | Vault Minerals' Genesis Minerals scheme of arrangement has already cleared shareholder vote and WA Supreme Court approval (per news context); a suspension notice at this stage reads as the routine administrative follow-on to an already-disclosed, already-priced-in merger timetable, not a new surprise. Not independently confirmed from the primary notice text. | LISTING verified (ASX feed) / CONTENT headline only — not accessed |
| MQG | 7:00pm | Ceasing to be a substantial holder (in some other entity) | N | Routine; new vs. 1907 cutoff but immaterial | LISTING verified / not read |
| CHC ×3, FTI, QFE | 7:05–7:13pm | Director's interest / unquoted-securities / quotation notices | N | Routine housekeeping | LISTING verified / not read |

## 4. Non-ASX-native catalyst check

Searched explicitly for US federal court/DOJ/DOE/CFIUS rulings or foreign regulatory actions affecting ASX-listed critical-minerals/resource names dated around 17 Nov 2026. Nothing found dated this week; most recent comparable items (Ioneer Rhyolite Ridge court win, American Battery Technology DOE grant reinstatement) are from March/June 2026 and already stale. No new finding this run — consistent with `1907_sweep.md`.

## 5. Source coverage

| Source | Status | Notes |
|---|---|---|
| `asx.com.au/asx/v2/statistics/todayAnns.do` | OK | Accessible this run; paginated in two ~100k-character fetches to cover the full day |
| TradingView `run-screener` | OK | Closing-session data, static since 16:00 close |
| TradingView `get-news` / `get-news-story` | OK | Used for LFT, VAU context |
| Web search | OK | Used to confirm VAU/Genesis scheme status, LFT drilling history, non-ASX-native sweep |
| Primary ASX PDF documents | Not attempted this run | Post-close; no time-critical need given LISTING-level confirmation sufficed |

## 6. Bottom line

No new price-sensitive catalyst that changes tonight's trading (market closed). Two late lodgements worth carrying into tomorrow's pre-open sweep: **LFT**'s drilling results (45m @ 2.71% Li₂O, headline-sourced) and **VAU**'s Suspension from Quotation (likely routine scheme-completion mechanics, not independently confirmed). Five liquid movers (STP, EGR, INN, SKK, RML) remain genuinely unexplained after a second, explicit full-day announcement check — flag for continued follow-up, especially SKK (largest traded value among the unexplained group).

---

*Research/screening tool only. This report does not constitute financial advice and contains no recommendation to buy, sell, or hold any security.*
