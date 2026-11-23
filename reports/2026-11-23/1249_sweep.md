# ASX SWEEP — Monday 23 November 2026

**Actual scan time:** 12:49pm AEDT (Melbourne). **Previous report:** reports/2026-11-23/1017_sweep.md — stated window "9:35am–10:15am"; **W (window end) = 10:15am** (report gave no scan-end timestamp other than its stated coverage range; using the coverage-range end per instructions).
**Data timestamp:** TradingView screener queried 12:49pm AEDT 23 Nov 2026, `update_mode: "streaming"` on all returned rows.
**TradingView relative volume — methodology unverified.**
**Liquidity rule:** traded value ≥ A$100,000 AND market cap ≥ A$5m.
**Reconciliation:** Screener rows: gainers 9 + losers 8 = 17; A 2 + B 0 + C 15 + D 0 + E 0 = 17.
Research/screening tool only — not financial advice.

---

## Category A — Confirmed liquid movers

| Ticker | Company | Chg | Rel.vol (unverified) | Traded value | Mkt cap (source) | Catalyst | Listing time | Flags / source | Key risk |
|---|---|---|---|---|---|---|---|---|---|
| ACW | Actinogen Medical | +55.56% | 2.01 | A$931,781 | A$34,827,915 (asx.api.markitdigital.com/.../ACW/header) | **UNEXPLAINED — RESEARCH REQUIRED.** Zero ACW rows in today's 370-row ASX listing (7:30am–12:40pm) and zero dated-today TradingView news items. Most recent news: 19 Nov XanaMIA topline — primary endpoint "numerically, but not statistically" superior to placebo (missed), positive subgroup (30% slowing) in older patients; Canaccord Genuity cut target price 50% to A$0.04 same day. No new-information trigger identified for today's move in either feed. | n/a (no row today) | LISTING: verified for today (absence confirmed against full 370-row listing); 19 Nov row time not independently re-verified this run (carried forward). CONTENT: read, 19 Nov doc idsId 03167608, pdftotext 42,650 chars from announcements.asx.com.au/asxpdf/20261119/pdf/076s82q9dnvg97.pdf | Move may be momentum/short-covering/speculation unrelated to disclosed fundamentals, which recently skewed negative (missed endpoint, target cut) |
| WAU | WA Gold | +20.83% | 5.03 | A$121,312 | A$15,157,243 (asx.api.markitdigital.com/.../WAU/header) | Verified: binding Scheme Implementation Deed with Leeuwin Metals (LM1) for 100% acquisition; combined ~896koz Au resource (Marda ~378koz + Abercromby ~518koz); scrip 0.0853 LM1 per WAU share, implied A$0.0179, 49% premium to A$0.012 last close; implied fully-diluted equity value ~A$25.7m; directors unanimously recommend absent Superior Proposal; targeted implementation Q1 CY2027 | 9:37am | LISTING: verified (today's listing, idsId 03169017). CONTENT: read, pdftotext 525,650 chars from announcements.asx.com.au/asxpdf/20261123/pdf/076xpmrjrnf91p.pdf (upgrades 1017_sweep.md:28's "not verified beyond headline") | Scheme conditional on shareholder vote + Independent Expert opinion; ~4-month-plus timeline; scrip consideration exposes holders to LM1 share-price risk |

## Category B — Cap not verified
None this scan — the only two rows clearing the A$100k traded-value bar (ACW, WAU) both returned a verified market cap from the ASX header API.

## Category E — Data conflicts
None this scan — ACW and WAU screener change% matched the ASX header `priceChangePercent` exactly; WAU volume matched exactly; ACW volume differed ~4.9% (66.56m screener vs 63.46m header), below the 5-percentage-point conflict threshold and not a change-percent conflict.

## Categories C and D
C (traded value < A$100k): 15 rows, no market cap check required. D (traded value ≥ A$100k but cap < A$5m): 0 rows.
Top 5 by traded value (descending): ENV −50.00% $74,081 | CML −17.50% $45,209 | AM3 +50.00% $42,099 | MML −54.55% $39,946 | AXI +25.00% $35,861.
Note: MML's listed drop coincides with its own 9:53am $4.04m partially-underwritten entitlement offer (idsId 03169046, read) lodged today — a plausible but not independently confirmed dilution-related driver.

---

## Overlap: price-sensitive announcements, W−45min (9:30am) through scan time (12:49pm)

37 price-sensitive rows retrieved in this window; 107 non-price-sensitive rows in the same window are not individually assessed (count only).

| Time | Ticker | Headline | PS | idsId | Grep result | Classification |
|---|---|---|---|---|---|---|
| 9:30am | IBR | Updated Iron Bear Project PFS | Y | 03169008 | no match | MISSED BY EARLIER REPORT — doc read (494,471 chars): NPV raised USD9.0B→11.6B (+29%) |
| 9:32am | PEN | Trading Halt | Y | 03169010 | 0935_full.md:196 | DEDUPLICATED |
| 9:34am | TAR | Soils and rock chips outline gold targets across Weioko | Y | 03169012 | no match | MISSED BY EARLIER REPORT — doc read (138,187 chars): East Normanby gold project soil/rock-chip anomalies |
| 9:37am | VMM | EU Commissioner Reaffirms Support for the Colossus Project | Y | 03169018 | 1017_sweep.md:31 | DEDUPLICATED |
| 9:37am | WAU | Transformational Transaction with Leeuwin Metals Ltd | Y | 03169017 | 1017_sweep.md:28 | DEDUPLICATED (see Cat. A — doc now read in full) |
| 9:37am | LM1 | WAU: Transformational Transaction with Leeuwin Metals Ltd | Y | 03169017 | 1017_sweep.md:28 | DEDUPLICATED (same idsId as WAU row, cross-tagged) |
| 9:40am | STX | Permian Gas Discovery Enhances Strike Acreage Potential | Y | 03169024 | 1017_sweep.md:30 | DEDUPLICATED — doc read resolves earlier "ticker mismatch" doubt: legitimate STX release re Hancock's Aulenti-1 well near Strike's own Perth Basin acreage |
| 9:42am | PCX | Dividend/Distribution - PCX | Y | 03169030 | no match | MISSED BY EARLIER REPORT — doc read (12,321 chars): Pengana Global Private Credit Trust distribution notice (routine) |
| 9:42am | UNT | Trading Halt | Y | 03169029 | 1017_sweep.md:34 | DEDUPLICATED |
| 9:42am | QML | High-Grade Copper Discovered 180m Beyond Mt Chalmers | Y | 03169027 | 1017_sweep.md:32 | DEDUPLICATED — doc read (75,904 chars): 12m@2.83% Cu incl 2m@7.05% Cu |
| 9:43am | SHG | Trading Halt | Y | 03169031 | 1017_sweep.md:34 | DEDUPLICATED |
| 9:46am | AIS | Aeris Restructures Guarantee Facility | Y | 03169034 | 1017_sweep.md:32 | DEDUPLICATED — doc read (5,868 chars): $50m Swiss Re facility refinances WHSP guarantee |
| 9:49am | GSS | TOV: GSS - Panel Application Withdrawn | Y | 03169039 | no match | MISSED BY EARLIER REPORT |
| 9:49am | BDX | TOV: GSS - Panel Application Withdrawn | Y | 03169039 | no match | MISSED BY EARLIER REPORT (same idsId as GSS row, cross-tagged) |
| 9:50am | MGH | Pause in Trading | Y | 03169040 | 1017_sweep.md:34 | DEDUPLICATED |
| 9:52am | SND | Saunders Announces Full Earn-Out Achievement | Y | 03169044 | 1017_sweep.md:32 | DEDUPLICATED — doc read (3,059 chars): Aqua Metro earn-out achieved in full |
| 9:53am | MML | Investor Presentation | Y | 03169050 | no match (ticker named at line 32 only re entitlement offer, not this doc) | MISSED BY EARLIER REPORT — distinct document from the one cited |
| 9:53am | MML | A$4.04 million Partially Underwritten Entitlement Offer | Y | 03169046 | 1017_sweep.md:32 | DEDUPLICATED — doc read (18,170 chars) |
| 9:54am | TEA | Pause in Trading | Y | 03169051 | 1017_sweep.md:34 | DEDUPLICATED |
| 9:56am | HIQ | Additional Funding under Loan Facility | Y | 03169052 | 1017_sweep.md:32 | DEDUPLICATED — doc read (6,470 chars): extra loan funding + proposed convertible notes |
| 9:58am | BPT | Pause in Trading | Y | 03169055 | 1017_sweep.md:27 | DEDUPLICATED |
| 10:01am | PPE | PPE AGM Address | Y | 03169057 | no match | MISSED BY EARLIER REPORT |
| 10:03am | PNV | NovoSorb BTM Achieves Pivotal Trial Endpoints, PMA Submitted | Y | 03169062 | 1017_sweep.md:29 | DEDUPLICATED — doc read (11,387 chars) confirms: PMA filed with FDA, trial 94.9% vs 87.3% SOC wound closure |
| 10:05am | BPT | Response to media speculation | Y | 03169066 | 1017_sweep.md:27 | DEDUPLICATED — doc read (1,718 chars): Beach **confirms** it is in discussions with Santos (STO) re acquiring certain Santos Taroom interests, upgrading earlier report's "could be a denial" to confirmed active talks |
| 10:08am | GRV | Field Testing of Uranium Targets commences Henbury Project | Y | 03169069 | 1017_sweep.md:32 | DEDUPLICATED — doc read (73,148 chars) |
| 10:09am | SNS | 2026 AGM - Chair's Address | Y | 03169073 | no match | MISSED BY EARLIER REPORT |
| 10:16am | IMA | Pause in Trading | Y | 03169078 | — (T>W) | NEW |
| 10:18am | TEA | Trading Halt | Y | 03169080 | — (T>W) | NEW (escalated from 9:54am pause) |
| 10:22am | P1E | 24 Zeus Electric Van Orders received - Sales Momentum Builds | Y | 03169081 | — (T>W) | NEW |
| 10:25am | INN | Innovaero Management Team Changes | Y | 03169083 | — (T>W) | NEW |
| 10:31am | MGH | Trading Halt | Y | 03169088 | — (T>W) | NEW (escalated from 9:50am pause) |
| 10:44am | IMA | Trading Halt | Y | 03169101 | — (T>W) | NEW (escalated from 10:16am pause) |
| 10:47am | LPE | CEO Appointment | Y | 03169102 | — (T>W) | NEW |
| 11:19am | KKC | Dividend/Distribution - KKC | Y | 03169115 | — (T>W) | NEW |
| 11:38am | HMX | Implementation of the Demerger | Y | 03169121 | — (T>W) | NEW |
| 11:41am | L1M | Pause in Trading | Y | 03169123 | — (T>W) | NEW |
| 11:45am | L1M | Trading Halt | Y | 03169125 | — (T>W) | NEW (escalated from 11:41am pause) |

Non-ASX-native catalyst check (mandatory): WebSearch run for US court/DOJ/FDA/DOE actions affecting ASX critical-minerals/resources names today; no results dated 23 Nov 2026 returned (closest matches were Ioneer, Mar 2026, and Dateline Resources, Jul 2026 — both stale).

---

## Source coverage

| Source | Status | Detail |
|---|---|---|
| ASX todayAnns listing | OK | Single curl, 660KB, 370 rows, 7:30am–12:40pm, not paginated/truncated |
| ASX per-company listing (ACW, WAU) | OK | Both returned prior-week history; ACW shows no row today |
| ASX header API (market cap) | OK | ACW, WAU both returned marketCap, volume, priceChangePercent with HTTP 200 |
| ASX documents (PDF→text) | OK | 16/16 downloaded (HTTP 200), 16/16 text-extracted (pdftotext, all >500 chars), 16/16 used |
| TradingView screener | OK | Two calls (gainers ≥+15%, losers ≤−15%, both relvol≥2), 9 + 8 rows, neither truncated at limit 40 |
| TradingView news | OK | ACW (53 items, none dated today), WAU/LM1 (1 item) |
| Company IR / mirrors | Not needed | ASX source sufficient for all documents attempted |
| Web search (non-ASX-native) | OK | No results dated today; see note above |

**Document table** (idsId | ticker | pdfURL | HTTP | bytes | extracted chars | used?):
03169017|WAU/LM1|.../076xpmrjrnf91p.pdf|200|1,788,142|525,650|yes
03167608|ACW|.../076s82q9dnvg97.pdf (19 Nov)|200|1,165,449|42,650|yes
03169024|STX|.../076xq47y00jkb8.pdf|200|484,147|17,453|yes
03169018|VMM|.../076xppwxy1bf4c.pdf|200|565,444|17,415|yes
03169069|GRV|.../076xtd6gqr8pgf.pdf|200|1,634,834|73,148|yes
03169027|QML|.../076xqbzyvly1qw.pdf|200|2,137,888|75,904|yes
03169034|AIS|.../076xqvp4080t27.pdf|200|126,919|5,868|yes
03169052|HIQ|.../076xs4pzj5gxd7.pdf|200|255,465|6,470|yes
03169044|SND|.../076xrkwzhb94d4.pdf|200|221,614|3,059|yes
03169046|MML|.../076xrqbzfgy17g.pdf|200|359,038|18,170|yes
03169008|IBR|.../076xnz9qj7gdpd.pdf|200|9,949,922|494,471|yes
03169012|TAR|.../076xp8lp0sjv83.pdf|200|2,923,703|138,187|yes
03169030|PCX|.../076xqkd0zm6l5n.pdf|200|17,288|12,321|yes
03169055|BPT(pause)|.../076xsch4kmxzrr.pdf|200|114,816|538|yes
03169066|BPT(response)|.../076xt54mcmxz02.pdf|200|81,726|1,718|yes
03169062|PNV|.../076xsw7mdm1n8n.pdf|200|203,907|11,387|yes

Gaps: 21 of the 37 price-sensitive overlap announcements (the "NEW" T>W set plus the remaining already-dedup'd/trivial halts) were not individually document-fetched this run — capped at 15 new document fetches per the ladder's limit, prioritised toward the liquid-mover explanation (ACW/WAU) and previously-unassessed items.

---
Tools called outside Bash/Read/Write/Edit/Glob/Grep/WebFetch/WebSearch/ToolSearch and the TradingView read tools (run-screener, get-symbol-data, get-news, get-news-story): none.
