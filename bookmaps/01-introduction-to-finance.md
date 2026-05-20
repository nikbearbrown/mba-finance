# Source map — Chapter 1: Introduction to Finance

*Trace from OpenStax source modules to chapter sections. Used during verification and revision.*

---

## Source files

All from `chapters/01-introduction-to-finance/`, in OpenStax module order:

| File | Module | OpenStax section title | Word count |
|---|---|---|---|
| `01-m00001.md` | m00001 | Chapter intro / Bacon Signs | 364 |
| `02-m00002.md` | m00002 | What Is Finance? | 3,284 |
| `03-m00003.md` | m00003 | The Role of Finance and the Financial Manager | 1,259 |
| `04-m00004.md` | m00004 | Companies in the Global Marketplace (Data + digitization) | 1,433 |
| `05-m00005.md` | m00005 | Careers in Finance | 1,072 |
| `06-m00006.md` | m00006 | Markets: Past to Present | 1,472 |
| `07-m00007.md` | m00007 | Microeconomics and Macroeconomics in Finance | 1,287 |
| `08-m00008.md` | m00008 | Financial Instruments | 1,957 |
| `09-m00009.md` | m00009 | The Concept of Time and Value | 1,470 |
| **Total** | | | **13,598** |

---

## Section-level mapping (rewrite → source)

### Chapter opening — *The puzzle of Bacon Signs*

- **Source:** m00001 (Bacon Signs hook), m00002 §"Definition of Finance"
- **Treatment:** Preserved Bacon Signs case verbatim in spirit, recast in workshop voice. Added the framing — *demand exceeded existing capital* — that makes the case land as a finance puzzle rather than a heroic-CEO story.
- **Footnote:** D&B Business Directory citation kept.

### Concept 1 — *What "finance" actually means*

- **Source:** m00002 §"Basic Areas in Finance" (business finance, investments, markets/institutions); m00003 §"The Finance Function" (controller/treasurer/VP-F/CFO).
- **Treatment:** Three-job framing is workshop framing, not OpenStax framing — OpenStax names the three areas but does not call out that the *word* "finance" is doing three jobs. Specification move ("Money," "Risk," "Value") is workshop addition; values-pulling-apart is implicit in OpenStax m00009 but never made explicit there.
- **Three balance-sheet decisions:** lifted from m00002 §"Business Finance" — working capital, capital budgeting, capital structure. Region-mapping mnemonic is workshop addition.

### Concept 2 — *Risk and expected return*

- **Source:** m00002 §"Risk and Return in Finance"
- **Treatment:** OpenStax makes the claim ("an increase in risk results in an increase in expected return") but does not unpack the missing words. The chapter's "three words missing" framing is workshop addition. The five risk types (default, inflation, diversifiable, non-diversifiable, political) come directly from m00002 vocabulary.
- **$10,000 over 30 years worked example:** workshop construction, illustrative not from source. Numbers checked against `(1.02)^30 = 1.8114` and `(1.06)^30 = 5.7435`. `[verify]` standard-deviation language for index funds — figure rendered against historical equity data; specific dispersion claim ("$25K to $130K with 80% probability over 30 years") needs primary-source check from a Monte Carlo simulation before publication.

### Concept 3 — *Where finance happens*

- **Source:** m00006 (primary/secondary, brokers/dealers/intermediaries); m00008 (money markets, capital markets, instruments)
- **Treatment:** Direct rewrite, condensed. Kept the car-market analogy from m00006 and added the limit ("doesn't capture how secondary-market prices feed information back"). m00007 (micro/macro economics) was *not* preserved as a standalone section — its content was folded into the broader synthesis, since the chapter focus is finance and macro returns in Ch 3.
- **Apple buy trace worked example:** workshop construction, illustrative.

### Synthesis

- **Source:** Distributed across m00002, m00009.
- **Treatment:** Workshop framing — *finance is the study of trade-offs over time under uncertainty.* Forward-pointers structured to actual book outline.

### Exercises

- **Source:** None directly — OpenStax exercises in source modules are referenced but not rendered (`[\#](#)` placeholders).
- **Treatment:** Workshop construction. Graduated structure (warm-up → application → synthesis → challenge) per the chapter spec. Numbers in 1.4 require students to compute `(1.04)^10 = 1.4802` and `(1.08)^10 = 2.1589`.

---

## Deferred from source — not used in the rewrite

- **Peloton case (m00004)** — moved to pantry/01 as reusable for Ch 11 or Ch 17.
- **Career detail and BLS salary data (m00005)** — too specific and dated to anchor a finance pedagogy chapter; flagged for an appendix or sidebar.
- **Microeconomics/Macroeconomics section (m00007)** — folded as a brief mention in the synthesis. Detailed treatment belongs in Chapter 3.
- **Time value introduction (m00009 §"Impact of Time on Saving and Spending")** — deferred entirely to Chapters 7–9, where TVM is built from scratch. The four-scenarios table in m00009 is preserved in pantry/01 as a hook candidate for Ch 7.
- **DJIA milestones table (m00009)** — moved to pantry/01 as reusable.

## Verification flags

- `[verify]` Treasury auction volume statistic ("hundreds of billions annually"). Refresh from TreasuryDirect for current year.
- `[verify]` 80% confidence interval claim on 30-year equity outcomes. Needs Monte Carlo or empirical-distribution citation.
- `[verify]` Damodaran data vintage when Figure 1.3 is rendered.

## Voice-anchor status

This chapter is one of the first written in this book and is part of the voice-setting exercise. No `style/` samples exist yet at root or per-book level. Drafted under workshop CLAUDE.md §6 default register — *explanatory with a view, conversational authority, "smartest friend at coffee."* Per Bear's accept of path C ("early chapters will need revision once voice settles"), expect revision pass after 3–5 chapters in.
