# HISTORICAL TEST — NOT CURRENT RESEARCH

**Purpose:** Test-mode validation of the overlap/dedup methodology (standing instruction, triggers only on Melbourne date 2026-11-17/18). This simulates a scan at **10:15am on 17 Nov 2026**, whose preceding report is `reports/2026-11-17/0936_full.md` (actual stated cutoff from its header: "Scan time: ~09:36 AEDT"; "Window covered: ... through ~9:35am"). Overlap window simulated: **cutoff − 45min (~08:50) through 10:15am**.

This file does not contain current trading research; it is a methodology self-check only.

---

## Method

Leads to confirm, per standing instruction: IOV "Amazon Funded POC..." (~09:09), IOV "Response to ASX Price Query" (~09:40), MYX Scheme Implementation Deed/Gedeon Richter (~09:15), PDI exploitation permits, TNE FY26 result. Each was checked against `grep` of `0936_full.md`, and cross-referenced against `1015_sweep.md`.

## Results

| Lead | Lodged | In window (08:50–10:15)? | In `0936_full.md`? (grep) | In `1015_sweep.md`? | Classification |
|---|---|---|---|---|---|
| MYX — Scheme Implementation Deed, Gedeon Richter A$6.40/sh | ~08:30–09:25 | Yes | **Yes** — lines 16, 19, 34, 294, 315 (full Section 1 #1 writeup) | Yes (referenced as "initial reaction," line 16) | **DEDUPLICATED** — already covered in `0936_full.md`, correctly not re-reported as new in `1015_sweep.md` |
| PDI — Bankan & Mansounia Exploitation Permits granted | ~09:26 | Yes | **Yes** — lines 38, 41, 43, 45, 53 (Section 1 #2) | Yes (line 17) | **DEDUPLICATED** |
| TNE — FY26 result, PBT +20%, record dividend | ~08:27–08:59 | Yes | **Yes** — lines 57, 60, 72, 238, 285 (Section 1 #3) | Yes (line 18) | **DEDUPLICATED** |
| IOV — "Amazon Funded POC Achieves 99% Cost Reduction" | ~09:09 | Yes (before 0936's own 9:35 cutoff) | **No match** — zero `IOV` hits anywhere in `0936_full.md` | No — `1015_sweep.md` only mentions the later price-query response (line 36), not this original PoC release | **RECOVERED** — lodged inside `0936_full.md`'s own coverage window but absent from it; would be flagged "missed by earlier report" under the live methodology. Confirmed independently via TradingView news (Small Caps article referencing a pre-open PoC announcement) and via `1653_sweep.md`'s own later regression check (lines 79–84 of that file), which separately identified this as a gap in `0936`/`1015`/`1244`/`1545`/`1638`. |
| IOV — "Response to ASX Price Query" | ~09:40 | Yes (after 0936's 9:35 cutoff, before 10:15) | No (correctly absent — lodged after 0936's cutoff) | **Yes** — line 36, flagged with content noted as "could not be verified this run" | **NEW** — correctly treated as new in the next report, not a miss |

## Assessment

- **RECOVERED:** IOV PoC announcement (~09:09) — in window, absent from the preceding report, with grep evidence (zero hits) and independent corroboration. ✅
- **DEDUPLICATED:** MYX, PDI, TNE — all in window, all already fully written up in `0936_full.md` with line-number evidence, and correctly not re-reported as new in `1015_sweep.md`. ✅
- **NEW:** IOV price-query response — lodged after the simulated cutoff, correctly captured as new in `1015_sweep.md`.

**Verdict: PASS.** At least one omitted announcement (IOV PoC, ~09:09) was RECOVERED with evidence (absent from `0936_full.md` despite falling inside its stated coverage window), and at least one covered announcement (MYX, also PDI/TNE) was correctly DEDUPLICATED with line-number evidence from both reports. The overlap methodology, as specified, distinguishes these cases correctly on this sample.

**Caveat:** This is a retrospective check against reports already produced by earlier live runs this session (not independently re-run against the raw ASX feed from scratch), so it validates the *dedup logic* given the reports' existing content, not the *original announcement-sourcing* step in isolation. The IOV PoC gap was itself only closed in a much later sweep (`1653_sweep.md`), illustrating that even with correct dedup logic, a miss can persist across several intermediate sweeps if no run re-checks the original window specifically — consistent with the standing instruction's "never assume... grep the earlier reports to confirm" rule.

---

*Test-mode output only — not current trading research. See `1922_sweep.md` for tonight's actual sweep.*
