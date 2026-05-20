# Revision Notes

Track what you've added, removed, or rewritten here.

---

## 2026-05-08 — "With LLMs" full rewrite + enrichment run

**Book state:** B (source subfolders), with State C origin (OpenStax module dumps preserved as `mNNNNN.md` inside each numbered chapter folder).

**Author byline:** Nik Bear Brown.
**Voice plugin:** `feynman` (workshop default; book is voice-unanchored at start, calibrated through Ch 1-3, stable from Ch 4 onward).
**Source canonical:** OpenStax *Principles of Finance* (CC-BY) treated as canonical for this book — workshop CLAUDE.md §7 rule 2 ("aggregators are leads, not primary sources") relaxed for the rewrite phase. `[verify]` flags on any claim that pushes beyond source.

**Chapters written:** 20 (full rewrite, 1-20).
**Chapter 00 generated:** `00-claude-basics.md`.
**Running project selected:** Equity Research Report on a Chosen Public Company (demo company: Apple).

**Dig Deeper prompts added:** 42 (2 per chapter, Ch 0-20).
**LLM Exercises added:** 21 (1 per chapter, Ch 0-20).

### Chapter log

| Chapter | Word count | Status |
|---|---|---|
| 00-claude-basics | 4,520 | generated + enriched (2 Dig Deepers) |
| 01-introduction-to-finance | 6,370 | written + enriched | OK |
| 02-corporate-structure-and-governance | 6,724 | written + enriched | OK |
| 03-economic-foundations-money-and-rates | 6,707 | written + enriched | OK |
| 04-accrual-accounting-process | 6,360 | written + enriched | OK |
| 05-financial-statements | 6,113 | written + enriched | OK |
| 06-measures-of-financial-health | 6,016 | written + enriched | OK; resolved a 3-way ROE discrepancy in source (32% vs. 36.4% vs. 26.4%) by picking the cleanest computation (32%) and logging in bookmap |
| 07-time-value-of-money-i-single-payment-value | 5,227 | written + enriched | OK |
| 08-time-value-of-money-ii-equal-multiple-payments | 4,767 | written + enriched | OK |
| 09-time-value-of-money-iii-unequal-multiple-payment-values | 4,531 | written + enriched | OK |
| 10-bonds-and-bond-valuation | 5,357 | written + enriched | OK |
| 11-stocks-and-stock-valuation | 5,776 | written + enriched | OK; project's analytical centerpiece |
| 12-historical-performance-of-us-markets | 4,471 | written + enriched | OK |
| 13-statistical-analysis-in-finance | 4,606 | written + enriched | **FLAGGED**: subagent source summary exceeded retrieval window; chapter written from preview + standard finance pedagogy (mean, variance, correlation, Sharpe — universal formulas). All worked examples self-consistent. Recommend extra source-comparison pass during review |
| 14-regression-analysis-in-finance | 4,781 | written + enriched | OK; **deviation logged**: workshop adds CAPM proper (security market line, cost-of-equity computation) because OpenStax modules don't develop CAPM explicitly. Defensible given chapter's role for Ch 17 and the project |
| 15-how-to-think-about-investing | 4,679 | written + enriched | OK; **deviation logged**: workshop adds explicit IPS framework, glide paths, active-vs-passive empirical case (SPIVA data). OpenStax under-engages these |
| 16-how-companies-think-about-investing | 4,611 | written + enriched | OK |
| 17-how-firms-raise-capital | 4,992 | written + enriched | OK; **deviation logged**: workshop adds pecking order theory and net-debt practitioner discussion |
| 18-financial-forecasting | 4,495 | written + enriched | OK |
| 19-the-importance-of-trade-credit-and-working-capital-in-planning | 4,106 | written + enriched | OK |
| 20-risk-management-and-the-financial-manager | 4,697 | written + enriched | OK; **deviation logged**: workshop adds enterprise risk management framework (risk register, risk appetite, transfer/avoid/mitigate/accept). OpenStax doesn't engage ERM as a structured framework |
| **TOTAL** | **109,906 words** | 21 chapters |

### Operational deviations from pasted-prompt spec (logged for review)

1. **No auto-cleanup of source subfolders.** Pasted prompt said delete `chapters/NN/` after verification; workshop preserved source. Deletion deferred to manual review.

2. **File naming: `chapters/NN-slug.md`** (matching subfolder name) instead of workshop CLAUDE.md's `YYYY-MM-DD-chapter-slug.md` convention. Per pasted-prompt spec for "with-llms" series; deviation noted.

3. **OpenStax treated as canonical source** instead of "lead to primary sources" per workshop CLAUDE.md §7 rule 2. Done with explicit acknowledgement in `book.md`. `[verify]` flags throughout for claims that push beyond source.

### Enrichment additions

**LLM Exercises (chapter-end, project-driven):** Each chapter ends with one. The 21 exercises form the project arc — each produces one section of the final equity research report. By Chapter 20, the LLM Exercises have produced (with the student's editing and judgment) a complete report.

**Dig Deeper prompts (inline, optional):** 2 per chapter, distributed across sections. Topics chosen to engage what the chapters foreshadowed but didn't fully develop. Topics covered:
- Ch 1: Knightian uncertainty; equity premium puzzle
- Ch 2: Dual-class shares; stakeholder capitalism
- Ch 3: Real interest rate transmission; Phillips curve breakdown
- Ch 4: ASC 606 reform; earnings management vs. fraud line
- Ch 5: Non-GAAP measures; goodwill impairment
- Ch 6: Industry ratio benchmarks; earnings-quality red flags
- Ch 7: Negative interest rates; social discount rate
- Ch 8: Gordon model assumptions; mortgage prepayment
- Ch 9: Multiple-IRR problem; terminal-value dominance
- Ch 10: Duration math; 2022-2024 yield curve inversion
- Ch 11: Why Berkshire/Amazon don't pay dividends; when DCF and multiples disagree
- Ch 12: Survivorship bias and the equity premium; sequence-of-returns risk
- Ch 13: Volatility drag; fat tails and 2008
- Ch 14: Bayesian beta shrinkage; Fama-French factors
- Ch 15: Behavioral finance; the 4% rule
- Ch 16: Real options; corporate hurdle rates above WACC
- Ch 17: Implied cost of capital; buybacks vs. dividends
- Ch 18: Forecast optimism bias; Monte Carlo simulation
- Ch 19: JIT and 2020-2022 supply chain stress; supply chain finance / Greensill
- Ch 20: Black Swans / Taleb; hedging programs that became speculation
- Ch 0: Prompt engineering for finance; when not to use an LLM

### Verification flags requiring human review

Listed in each chapter's `bookmaps/NN-slug.md` under "Verification flags." Categories:

- **Numerical data:** specific historical figures (S&P 500 returns by decade, Apple balance-sheet figures, Damodaran ERP estimates, etc.) need refresh against current vintage data before publication.
- **Recent events:** the 2022-2024 macro narrative used for currency in Ch 3, 12, 17, 18. Will date over time; designed to be refreshed.
- **Real-firm specifics:** Apple, 3M, Coca-Cola, etc. — figures are illustrative; verify against current 10-Ks before publication.
- **Footnote citations:** verify all academic-paper citations are real (LLMs sometimes invent these; a separate review pass should confirm each one).

### Pending work

- **Production review** of all 21 chapters for voice consistency across the book.
- **Verification pass** on `[verify]` flags throughout chapters.
- **Citation check** on academic and journal references in Dig Deeper prompts.
- **Figure design** from the briefs in `images/`.

### Outputs at end of run

- 21 chapter files (`chapters/00-*.md` through `chapters/20-*.md`).
- 20 pantry files (`pantry/01-*.md` through `pantry/20-*.md`; Ch 0 is meta and doesn't need pantry).
- 20 image briefs.
- 20 bookmap source-trace files.
- `book.md`, `chapter-map.md`, `_toc.md`, this `_notes.md`.

Run completed 2026-05-08.
