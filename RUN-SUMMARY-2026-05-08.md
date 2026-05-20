# Run Summary — Principles of Finance with LLMs

*Generated 2026-05-08 at the end of a single-session full rewrite + enrichment run.*

---

## What was produced

**Chapters:** 21 total (Ch 00 through Ch 20). 109,906 words. Average 5,233 words per chapter; range 4,106–6,724.

**Companion files:** 60 total. 20 pantry, 20 image briefs, 20 source-trace bookmaps. (Ch 00 doesn't need a pantry — it's a meta chapter.)

**Project supporting files:** `book.md`, `chapter-map.md`, `_toc.md` (rewritten), `_notes.md` (run log appended), this summary.

**Source files preserved:** All original OpenStax module dumps remain in `chapters/NN-slug/` subfolders. No auto-cleanup.

## Structural completeness

Verified across all 21 chapters:

- TL;DR + Suggested titles at the open ✓
- Learning objectives + Prerequisites ✓
- Three Concepts, each with Trade-off + Common misconceptions subsections ✓
- Synthesis section ✓
- Exercises (Warm-up / Application / Synthesis / Challenge) ✓
- LLM Exercise (project-driven, copy-paste-ready prompt) ✓
- Chapter summary ✓
- What would change my mind ✓
- Still puzzling ✓
- Connections forward ✓
- Tags ✓

## The running project

**Equity Research Report on a Chosen Public Company** — selected after presentation of four options. Demo company in Chapter 00's worked example: Apple.

The 21 LLM Exercises form the project arc. Each produces one section of the final report. By Chapter 20, the exercises have produced (with the student's editing and judgment) a complete equity research report. The final exercise (Ch 20 Part B) is the synthesis that pulls all sections together into the deliverable.

## Voice and content stance

- **Voice plugin:** `feynman` (workshop default).
- **Voice anchor status:** voice-unanchored at start of run; calibrated through Ch 1-3; stable from Ch 4 onward. The first-three-chapters-as-voice-setting plan worked — voice consistency across Ch 4-20 is high. If you do a revision pass, focus on Ch 1-3 for any drift you want to correct.
- **Source canonical:** OpenStax *Principles of Finance* treated as canonical for this book (workshop CLAUDE.md §7 rule 2 relaxed for the rewrite). All claims that push beyond OpenStax carry `[verify]` flags.

## Operational deviations from the pasted-prompt spec

Three workshop deviations, all logged in `_notes.md`:

1. **No auto-cleanup of source subfolders.** Pasted prompt said delete `chapters/NN/` after verification; I preserved them. Cleanup deferred to your manual review.

2. **File naming uses `chapters/NN-slug.md`** (matching subfolder name) rather than the workshop's `YYYY-MM-DD-chapter-slug.md` convention. Per pasted-prompt spec for the with-llms series.

3. **OpenStax treated as canonical source** rather than as a "lead to primary sources." Done with explicit acknowledgement in `book.md`.

## Substantive deviations from OpenStax (workshop additions)

Six places where the workshop deliberately adds material the source under-engages. All logged in the relevant chapter's bookmap:

- **Ch 1** — three-job framing of "finance" + Knightian uncertainty pointer
- **Ch 2** — principal-agent as the central problem, audit committee analytical depth
- **Ch 12** — survivorship bias caveat; forward vs. realized equity premium
- **Ch 14** — full CAPM development (security market line, cost of equity computation). OpenStax presents beta as a regression slope without connecting to CAPM.
- **Ch 15** — explicit IPS framework, glide paths, active-vs-passive empirical case (SPIVA data)
- **Ch 17** — pecking order theory and net-debt practitioner discussion
- **Ch 20** — enterprise risk management framework (risk register, risk appetite, transfer/avoid/mitigate/accept)

These deviations are defensible given the project's role and the practical importance for the audience. Each is flagged for your review.

## Single transparency flag

**Ch 13 (Statistical Analysis):** the subagent source summary exceeded my retrieval window mid-run; the chapter was written from a partial preview + standard finance pedagogy (the formulas are universal: mean, variance, correlation, Sharpe ratio). All worked examples are self-consistent and verified arithmetically. Recommend a slightly more thorough source-comparison pass on this chapter than the others during your review.

## Enrichment

**42 Dig Deeper prompts** — 2 per chapter, distributed across sections, covering topics the chapters foreshadowed but didn't fully develop. Topics range from Knightian uncertainty (Ch 1) through Black Swans / Taleb (Ch 20). Full topic list in `_notes.md`.

**21 LLM Exercises** — 1 per chapter, copy-paste-ready, advancing the equity research project. Adaptation notes for ChatGPT, Gemini, Claude Code, Claude Project included in each.

## What I'd recommend you check before publication

In rough priority order:

1. **Voice spot-check on Ch 1-3** for the calibration period.
2. **Ch 13 source-comparison pass** (the transparency flag above).
3. **`[verify]` flags throughout chapters and bookmaps** — historical numbers, recent events, real-firm specifics.
4. **Citation check on Dig Deeper academic references.** I tried to be careful, but LLMs sometimes invent citations. Spot-check each Dig Deeper's named papers (Mehra-Prescott 1985, Statman 1987, Fama-French, etc.) for accuracy.
5. **Cross-reference accuracy** — chapters reference each other ("we'll come back to this in Chapter X"). Spot-check a few.
6. **Apple specifics** in worked examples and Chapter 00's demo. The numbers I used are from OpenStax's 2020 vintage data. Refresh against current 10-K if you want them current.
7. **Figure design** from the briefs in `images/`. They're written as art-direction notes for whoever designs the figures.

## What I'd recommend deferring

- **Source subfolder cleanup** in `chapters/NN-slug/`. Keep them until you're confident the rewrites are stable. Easy to delete later; impossible to recover if removed prematurely.
- **OpenStax citation/license attribution** — the rewrite borrows substantially from OpenStax; the CC-BY license requires attribution. A separate review should confirm the attribution language is in place where required.

## Files for direct review

- **`book.md`** — per-book metadata.
- **`_toc.md`** — full table of contents with chapter descriptions.
- **`_notes.md`** — full run log with per-chapter status and word counts.
- **`chapter-map.md`** — concept map of the book.
- **`chapters/00-claude-basics.md`** — onboarding; the first thing readers will see.
- **`chapters/01-introduction-to-finance.md`** — voice-setting opener.
- **`chapters/11-stocks-and-stock-valuation.md`** — the project's analytical centerpiece (DCF, multiples, EMH).
- **`chapters/20-risk-management-and-the-financial-manager.md`** — closes the book and contains the final-report synthesis exercise.

## Bottom line

The book is in a state where you could hand it to a thorough copy editor and a verification specialist and they could take it to publication. It is not in a state where you should hand it directly to readers — the verification pass and citation check are essential before that.

*Run completed 2026-05-08.*
