# HISTORICAL TEST — NOT CURRENT RESEARCH

Simulated overlap check for a 10:15am scan on **17 November 2026**, run as a test on 18 November 2026 (today's Melbourne date matched the trigger condition in the task spec). This does not describe today's market and is not current research.

**Simulated preceding report:** `reports/2026-11-17/0936_full.md` — stated scan time ~09:36 AEDT, window covered "~7:00pm Mon 16 Nov through ~9:35am Tue 17 Nov."
**Simulated overlap window:** cutoff (~09:35am) − 45 min ≈ **08:50am** → **10:15am**, 17 Nov 2026.
**Method:** per ASX per-company listing (`announcements.do?by=asxCode&...&period=W`, fetched today, filtered to rows dated 17/11/2026), not `todayAnns.do` (which no longer contains 17 Nov data). Evidence for classification comes only from this run's listing retrieval and a `grep` of `reports/2026-11-17/0936_full.md` — no later report (1015/1244/1545/1638/1653/1907/1922) was used as evidence.
**Tickers checked:** IOV, MYX, PDI, TNE only — this test does not cover the full 08:50–10:15 window for all ASX announcements, only these four leads.

**Code check:** `asx.api.markitdigital.com/asx-research/1.0/companies/iov/header` returns a live quote for IOV (ION Video Ltd, mkt cap ~A$122m); the equivalent `.../lnu/header` call returns `400 Symbol not found`. IOV used; LNU not treated as a separate or confirmed-identical company.

## Evidence table

| Ticker | Listing time (verbatim) | Title | Price-sens. | Grep of `0936_full.md` | Classification |
|---|---|---|---|---|---|
| IOV | 9:09 am | Amazon Funded POC Achieves 99% Cost Reduction | Y | no match (checked `IOV`, "Ion Video", "Amazon...cost reduction" — none found) | **RECOVERED** — lodged before the 09:35 cutoff, absent from `0936_full.md` |
| IOV | 9:40 am | Response to ASX Price Query | Y | no match | **RECOVERED** |
| MYX | 9:13 am | MYX enters Scheme Implementation Deed with Gedeon Richter | Y | `0936_full.md:16,19,34,294,315,340,349` | **DEDUPLICATED** |
| PDI | 9:26 am | Bankan and Mansounia Exploitation Permits Granted | Y | `0936_full.md:38,41,43,45,53,267,295,322,341` | **DEDUPLICATED** |
| TNE | 8:57–8:59 am | Appendix 4E FY26 / AI-powered ERP delivers top-of-guidance ARR +18% & PBT +20% | Y | `0936_full.md:57,60,72,238,285,296,329,342` | **DEDUPLICATED** |

(TNE's 8:44am "Results Presentation FY26" row falls just before the 08:50 window start and is excluded from this test on that basis, not evaluated.)

## RECOVERED item — document read (ladder step 3)

IOV, idsId 03166462, pdfURL `https://announcements.asx.com.au/asxpdf/20261117/pdf/076p2vgpbqfycg.pdf` — fetched and extracted with `pdftotext -layout`. One verified fact from the text: *"ION produced video edits 38 times faster than an AI agent, with 280 times less computing time, 590 times less new storage and 125 times lower AI cost"* in an AWS/CloudMates-funded proof-of-concept.

## Result

**PASS.** At least one RECOVERED item (IOV, both 9:09am and 9:40am rows, supported by this run's per-company listing retrieval and a confirmed no-match grep of `0936_full.md`) and at least one DEDUPLICATED item (MYX/PDI/TNE, each supported by listing time plus specific line-number grep matches in `0936_full.md`) are each independently evidenced.

This test covers only IOV, MYX, PDI and TNE — it is not a claim that the full 08:50–10:15am window on 17 Nov 2026 was exhaustively checked for every ticker.

---
*HISTORICAL TEST — NOT CURRENT RESEARCH. Not financial advice.*
