# ASX POST-CLOSE SWEEP

**Date:** Tuesday, 17 November 2026
**Scan time:** ~16:53 AEDT (Melbourne) — note: this run's stored prompt describes it as a "midday (~12:30pm) sweep," but it actually fired at 16:53, after the ASX cash market close (~16:12 AEDT). Proceeding with the actual scan time; a genuine midday window was already covered by `1244_sweep.md`.
**Previous report's actual cutoff used:** `1638_sweep.md` — stated window "since the 15:45 full report cutoff," checked through its own ~16:34 cutoff.
**Data timestamp / feed status:** TradingView screener queried ~16:50 AEDT, `update_mode: "streaming"` on all rows (not delayed). Close/change figures reflect the completed cash-session close (~16:12 AEDT); nothing moves further until tomorrow's open.
**Volume basis:** `relative_volume_10d_calc` = today's cumulative volume vs the FULL-DAY 10-day average. Because the session is complete, this is not understated the way it would be mid-session. No separate same-time-of-day relative-volume column exists in the screener catalogue (checked via `get_screener_columns` search "relative volume" — only the one column, with bar-interval suffixes, not time-of-day-adjusted).

This is a research/screening tool, not financial advice. Nothing here is a recommendation to buy, sell, or hold any security.

---

## 1. Price-action movers (full-day change ≥15%, relative volume ≥2x)

| Ticker | Company | Price change | Rel. volume (10d, full-day basis) | Traded value (A$) | Verified catalyst | Announcement time | Source | Key risk |
|---|---|---|---|---|---|---|---|---|
| MYX | Mayne Pharma Group | +87.2% (close $6.01; prior close $3.21, confirmed via OHLCV) | 11.1x | ~$35.2m | **Verified, already covered.** Gedeon Richter A$6.40/share cash takeover scheme (A$604m equity value), board-recommended, lodged in a cluster of releases 09:15am–12:25pm today. Fully reported in `0936_full.md`, `1015_sweep.md`, `1545_full.md`, `1638_sweep.md`. The 87% figure is now independently confirmed as genuine (not a stale-baseline artifact as `1638` cautioned) — OHLCV shows prior close $3.21 → today's range $5.70–$6.02. | 09:15–12:25pm (multiple releases) | [Reuters/Dow Jones/Small Caps via TradingView news feed; ASX announcements, MYX, 17 Nov 2026] | Still trading below the $6.40 offer (arbitrage spread); scheme conditions (court/shareholder approval) not yet satisfied, targeted completion March 2027 |
| IOV | Ion Video Ltd | +20.1% (close $0.865) | 11.6x | ~$959k | **Verified — see Section 3 (IOV regression check).** Price-sensitive PoC results announcement (AWS-funded, claimed >99% cost reduction) lodged before market open; Response to ASX Price Query followed. | PoC results: before 10am open (exact lodgement time not independently confirmed from a primary ASX source — access failed, see Source coverage); Price Query response: Reuters-processed ~12:23pm | [TradingView news (Reuters, Small Caps); ASX announcements, IOV, 17 Nov 2026] | Results are a small internal benchmark test, not a signed commercial contract; company explicitly says the extrapolated cost savings don't represent a measured full-scale system |
| BKT | Black Rock Mining | +66.7% (close $0.015) | 10.5x | ~$127k | **Partially verified.** A second, separate funding announcement — "Interim funding secured via US$5m early draw-down of working capital facility" — lodged ~12:11pm today, distinct from the 9:45am "Early Works Funding Secured from CRDB" item already flagged in `1015_sweep.md`. This second release was not mentioned in `1244_sweep.md` or `1545_full.md` despite the stock's continuing move — **missed by earlier reports.** | ~12:11pm | [Reuters via TradingView news; ASX announcement, BKT, 17 Nov 2026] | Headline-only; facility terms/covenants, and why an "early draw-down" was needed, not verified against the primary PDF |
| RMX | Red Mountain Mining | +20.0% (close $0.012) | 26.7x | ~$321k | **Partially verified.** Halt reason now confirmed as "Trading halt requested for capital raising purposes" (lodged ~9:53am) — resolves the "reason not disclosed" gap flagged in `1015_sweep.md`. `get_symbol_data` shows RMX is NOT currently halted (`halt: null`, streaming), so it must have resumed trading intraday; no resumption/outcome announcement could be located this run. | ~9:53am (halt request) | [Reuters via TradingView news; ASX announcement, RMX, 17 Nov 2026] | Capital-raising outcome (pricing, size, dilution) unverified; today's price/volume move cannot be fully attributed without it |
| STP | Step One Clothing | +15.4% (close $0.15) | 18.9x | ~$186k | **UNEXPLAINED MOVER — RESEARCH REQUIRED.** No TradingView news item dated 17 Nov; web search (InvestSMART, MarketIndex, Fool.com.au) found no announcement past 21 Oct 2026 (change of company secretary). Stock has been under broker price-target cuts since a weak FY26 result; today's jump could be a technical/short-covering bounce rather than news-driven. | Not found | [TradingView news feed — no 17 Nov item found; web search] | No verified catalyst; move could reverse without a company announcement behind it |
| EGR | EcoGraf | +15.8% (close $0.22) | 4.1x | ~$105k | **UNEXPLAINED MOVER — RESEARCH REQUIRED.** No TradingView news or web search result dated 17 Nov 2026; most recent EGR item found was ~14 Oct 2026. | Not found | [TradingView news feed — no 17 Nov item found; web search] | No verified catalyst |
| INN | Innovaero Technologies | -21.4% (close $0.22) | 3.2x | ~$148k | **UNEXPLAINED MOVER — RESEARCH REQUIRED.** No TradingView news dated 17 Nov (latest: broker initiations, 1 Nov). Recently IPO'd (22 Sep 2026) defence-drone maker; thin post-IPO trading history makes single-day moves hard to benchmark. | Not found | [TradingView news feed — no 17 Nov item found; web search] | No verified catalyst; small post-IPO float can move sharply on thin news |
| SKK | Stakk Ltd | -18.75% (close $0.013) | 12.4x | ~$1.64m | **UNEXPLAINED MOVER — RESEARCH REQUIRED.** Largest traded-value decliner found. No TradingView news or web-search result dated 17 Nov; latest located item ~12 Oct 2026 (Q1 revenue). Given the heavy volume (125.9m shares) this is the single biggest coverage gap in this sweep. | Not found | [TradingView news feed — no 17 Nov item found; web search] | Largest unexplained move by traded value this run — do not assume this is just market beta without a confirmed catalyst |
| RML | Resolution Minerals | -15.6% (close $0.027) | 2.7x | ~$372k | **UNEXPLAINED MOVER — RESEARCH REQUIRED**, though plausibly consistent with a broad small-cap resource sell-off: many ASX junior resource names fell heavily today (EMU, SRN, BUR, DTZ, BOC among the illiquid decliners below) alongside the ASX 200's ~-1.8% session (per `1638_sweep.md`). This is an inference, not a verified company-specific cause. | Not found | [TradingView news feed — no 17 Nov item found; sector pattern inference] | Funding-dependent explorer; no confirmed company-specific news found |
| CAT | Catapult Sports | -16.6% (close $3.02) | 4.7x | ~$18.2m | **Verified, already covered extensively today** (`0816`, `0936`, `1015`, `1244`, `1545`, `1638`). H1 FY27 result: earnings +66%, ACV +25% to $145.2m, EBITDA margin 19.7% — but stock sold off, consistent with a result that looked strong on headline figures while disappointing against the market's prior expectations (classic "good headline, bad market reaction" case). Not re-litigated in depth this run. | Results released ~09:02am; stock fell through the session | [Dow Jones/Reuters via TradingView; prior reports] | Already flagged in earlier reports; no new information this run |

### Illiquid movers (traded value < A$100,000 or market cap < A$5m) — separate, not investigated in depth

| Ticker | Change | Close | Volume | Traded value | Market cap |
|---|---|---|---|---|---|
| MMR | +100% | $0.002 | 963,428 | ~$1,927 | $1.87m |
| IBX | +50% | $0.006 | 24,394,502 | ~$146,367* | $4.02m |
| AXI | +25% | $0.015 | 2,390,751 | ~$35,861 | $8.18m |
| NGY | +23.8% | $0.026 | 540,402 | ~$14,050 | $39.99m |
| T88 | +21.1% | $0.046 | 169,336 | ~$7,789 | $4.71m |
| FLC | +18.0% | $0.059 | 1,651,913 | ~$97,463 | $62.35m |
| IAM | +16.7% | $0.014 | 927,055 | ~$12,979 | $11.17m |
| 10X | +15.0% | $0.115 | 170,000 | ~$19,550 | $3.74m |
| SPX | -33.3% | $0.002 | 10,910,077 | ~$21,820 | $1.86m |
| QUE | -28.6% | $0.02 | 275,000 | ~$5,500 | $0.54m |
| CQT | -25.0% | $0.003 | 2,185,155 | ~$6,555 | $5.08m |
| RAD | -25.0% | $0.003 | 21,752,520 | ~$65,258 | $18.84m |
| N1H | -23.5% | $0.13 | 200,000 | ~$26,000 | $11.45m |
| BUR | -23.1% | $0.02 | 605,999 | ~$12,120 | $5.93m |
| ASH | -21.4% | $0.22 | 366,133 | ~$80,549 | $41.60m |
| DTZ | -21.4% | $0.011 | 1,418,895 | ~$15,608 | $8.64m |
| RLG | -20.0% | $0.004 | 15,100,655 | ~$60,403 | $12.11m |
| SRN | -20.0% | $0.012 | 698,546 | ~$8,382 | $3.39m |
| EMU | -18.2% | $0.009 | 1,194,803 | ~$10,753 | $4.87m |
| PMM | -16.3% | $0.18 | 161,866 | ~$29,136 | $16.10m |
| VMT | -15.8% | $0.08 | 357,472 | ~$28,598 | $38.28m |
| BOC | -15.6% | $0.135 | 152,615 | ~$20,603 | $64.17m |
| EVE | -15.4% | $0.011 | 2,870,030 | ~$31,570 | $4.58m |

*IBX and FLC flagged illiquid on market-cap/traded-value thresholds respectively (FLC's $97,463 traded value is just under the $100k cutoff).

Note: **ASH** (-21.4%, illiquid by traded value) was the subject of an "unreconciled figures" watchlist flag carried in `1545_full.md` — today's further decline is noted but not re-investigated given its illiquid status this run.

---

## 2. New/missed announcements (overlap window)

Window checked: 45 minutes before `1638_sweep.md`'s stated ~16:34 cutoff (i.e. from ~15:49) through now (~16:53).

- `1638_sweep.md` already covered this window in full down to its 16:34 cutoff (routine AGM/NTA/substantial-holder notices, plus VAU and MYX housekeeping items), concluding "No genuinely new, material/price-sensitive items found."
- The only genuinely new slice is ~16:34–16:53 today. The ASX announcements platform's active lodgement period for the day ends around 16:30–16:35 (per `1638_sweep.md`'s own observation that the last entries came before 16:34 "market housekeeping" cutoff), and this sweep's own source-access limitations (below) mean no primary feed could be polled live for this ~19-minute slice.
- The BKT 12:11pm funding announcement (Section 1) and the RMX halt-reason clarification are not inside this overlap window, but are flagged above as items missed by `1244_sweep.md`/`1545_full.md` under the "investigate every qualifying mover" rule, not the overlap rule.
- No new trading halts identified since `1638_sweep.md` (GAS, MAP, ACW remain the carried-forward unresolved halts from that report; no resumption confirmed this run).

**Conclusion: no new/missed price-sensitive announcements found in the genuine overlap slice (~16:34–16:53).** Sources worked (TradingView news checked specifically for this), nothing was there — this is a "no material news found" result, not a coverage failure.

---

## 3. IOV regression check (today = 2026-11-17, so this item runs)

| Lead | Status |
|---|---|
| (a) Company identity: "Ion Video Ltd", ASX:IOV | **Verified.** TradingView news consistently identifies the company as "Ion Video Ltd" (ASX:IOV), described in a Small Caps article as "The Melbourne technology developer" of video-editing software ("ION", "Programmable Video"). Market cap ~$84.9m. |
| (b) Price-sensitive PoC announcement ~9:09am titled something like "Amazon Funded POC Achieves 99% Cost Reduction" | **Verified in substance, exact time not independently confirmed.** A Small Caps article ("ION Video Drastically Cuts Editing Costs in Amazon-Funded Technology PoC Testing") and IOV's own Response to ASX Price Query both confirm a PoC results announcement was lodged "prior to market open on Nov 17," reporting >99% reductions in several video-editing resource/cost measures vs. two AI-agent comparators (Cursor, Google Gemini) in an AWS-funded test. The claimed ~9:09am lodgement time could not be confirmed against a primary ASX source — ASX's own announcements pages returned a 404/placeholder page to this session's web-fetch tool (see Source coverage). |
| (c) Price-query response ~9:40am | **Content verified; exact time not independently confirmed.** Reuters-sourced text: IOV "does not share the view" that recent trading suggests PoC results info "may have ceased to be confidential," and confirms the results were released in an announcement "prior to market open on Nov 17." This **does add information** beyond a bare "nothing to disclose" — it is a substantive (if boilerplate) denial of a leak, not just a pointer to the earlier release. Reuters' own processing timestamp for this item was ~12:23pm, which may reflect redistribution lag rather than the actual ASX lodgement time; the claimed ~9:40am lodgement time is plausible (consistent with a same-morning response) but not independently confirmed. |
| (d) Late-October trading halt → data-centre trial (Nordic operator / Priority Impact / Swinburne University) → A$4.25m placement | **Mostly verified, with one timing discrepancy.** Trading halt "pending announcement on strategic validation program and material commercial agreement" confirmed dated 26 Oct 2026. Follow-up "validation trial for data centres establishes clear pathway to commercialisation" confirmed dated 28 Oct 2026, and today's PoC article explicitly names Swinburne University of Technology (independent Nordic assessment) and Priority Impact founder/CEO Magnus Rosengren (A$1m commitment, Oct relationship). **However**, the A$4.25m oversubscribed placement (at $0.40/share) is dated 16 Sep 2026 — roughly six weeks *before* the late-October halt/trial sequence, not concurrent with it as the lead's phrasing implied. Treat the placement as a separate, earlier funding event, not part of the late-October news cluster. |
| IOV in today's screener? | **Yes, for the first time today.** IOV was not in any movers table in `0816`, `0936`, `1015`, `1244`, `1545`, or `1638` (the only earlier mention was a one-line, unverified announcement-table flag in `1015_sweep.md`, not a screener hit). It appears in this run's screener at +20.1%, rel. vol. 11.6x — consistent with the day's catalyst accumulating through the session rather than firing all at once at the open. |
| IOV in earlier reports today? | **Only `1015_sweep.md`**, as a one-line "Response to ASX Price Query... could not be verified" flag. Not carried forward or re-investigated in `1244_sweep.md` or `1545_full.md` despite the continuing price move — a gap in follow-through by those reports, now closed by this run. |

---

## 4. Source coverage

| Source | Status | Notes / errors |
|---|---|---|
| TradingView `run-screener` | OK | Streaming data, two queries (gainers ≥15%, decliners ≤-15%, rel. vol ≥2x), 14 + 19 rows respectively. |
| TradingView `get-screener-columns` (relative volume search) | OK | Confirms no separate time-of-day relative-volume column exists; only `relative_volume_10d_calc` with bar-interval suffixes. |
| TradingView `get-news` / `get-news-story` | OK | Primary source for MYX, IOV, BKT, RMX cause verification; full story text retrieved for several items. No 17-Nov item found for STP, EGR, INN, SKK, RML despite checking. |
| TradingView `get-symbol-data` (halt check) | OK | Confirmed RMX not currently halted. |
| TradingView `get-ohlcv` | OK | Confirmed MYX's 87% move is genuine (prior close $3.21) rather than a data artifact. |
| ASX announcements feed (direct, asx.com.au) | **Failed** | `asx.com.au/asxpdf/ancodes/IOV.html` redirected to `announcements.asx.com.au/asxpdf/ancodes/IOV.html`, which returned HTTP 404. `asx.com.au/markets/trade-our-cash-market/announcements` returned a JS-templated shell with no data (requires client-side rendering not available to this session's fetch tool). Consistent with the data-access limitations already logged in `1244_sweep.md` and `1015_sweep.md` for this environment. |
| Web search (aggregators: InvestSMART, MarketIndex, Fool.com.au, Stockhead) | Partial | Useful for historical context (STP broker cuts, INN IPO history, EGR patent/offtake history, SKK contract history) but these aggregators lag — none returned a 17 Nov 2026 item for STP, EGR, INN, SKK, or RML. Cannot distinguish "no news exists" from "not yet indexed" for these five names — logged as coverage gaps, not as "no material news found." |
| Non-ASX-native (US court/DOJ/federal-agency) catalyst search | OK — no new item found | Searched specifically; most relevant historical items (Dateline Resources/DOJ Colosseum Mine matter, MP Materials vs. USA Rare Earth litigation) are undated or predate November 2026; nothing new today. |

**Coverage gaps this run:** STP, EGR, INN, SKK, RML — cause of today's move could not be confirmed from any accessible source (ASX direct access failed; TradingView news and web aggregators had nothing dated 17 Nov for these five tickers). These are "sources inaccessible/incomplete," not "no material news found" — a genuine ASX announcement may exist that none of the available tools could surface. SKK (~$1.64m traded value, -18.75%) is the largest and most material of these gaps.

---

## 5. Bottom line

No new price-sensitive information surfaced in the genuine overlap window since `1638_sweep.md`'s ~16:34 cutoff — the ASX session is closed and the announcements platform's active lodgement period for the day has ended. The incremental findings this run are: (i) MYX's 87% jump is now confirmed genuine (not a data artifact) and remains fully explained by the Gedeon Richter takeover; (ii) a second BKT funding announcement (~12:11pm) and a clarified RMX halt reason (capital raising, ~9:53am) were found that earlier midday/afternoon reports missed; (iii) the IOV regression check substantially confirms the pilot's unverified leads — company identity, the AWS-funded PoC announcement, the price-query response's added substance, and the late-Oct halt/trial sequence are all verified, with one correction (the $4.25m placement predates, rather than accompanies, the late-October news cluster); and (iv) five movers (STP, EGR, INN, SKK, RML) remain genuinely unexplained due to source-access limitations in this environment, with SKK the most material gap by traded value.

---

*Research/screening tool only. This report does not constitute financial advice and contains no recommendation to buy, sell, or hold any security.*
