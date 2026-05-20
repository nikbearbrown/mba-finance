# Principles of Finance with LLMs

*Per-book metadata. Loaded by skills before drafting. Overrides workshop CLAUDE.md on voice specifics; subordinate on hard rules.*

---

## Title

**Principles of Finance with LLMs**

## Subtitle

A first course in business finance for the era of large language models.

## Audience

Sophomore or junior business undergraduates taking their first finance course. One semester of accounting and one semester of college algebra assumed. Statistics not assumed — built up from scratch in chapters 13–14. No coding background assumed.

Secondary audience: career-changers and self-learners working through the book outside a classroom, who want to learn finance and learn to use Claude as a financial-thinking partner at the same time.

## Scope

Twenty-chapter introductory finance course covering: the finance function, accounting and financial statements, time value of money, bond and stock valuation, market history, statistical and regression analysis as applied to financial data, capital budgeting, capital structure, financial forecasting, working capital, and risk management. Plus Chapter 00 — Claude Basics — as onboarding.

Out of scope: derivatives pricing, advanced portfolio theory, international finance, real estate finance, behavioral finance as a standalone treatment.

## Source

Faithful rewrite of OpenStax *Principles of Finance* (CC-BY licensed) in the workshop's Feynman voice, with an integrated "with LLMs" layer (Chapter 00, Dig Deeper prompts, end-of-chapter LLM Exercises tied to a running project).

For this book — and only this book — OpenStax is treated as canonical source rather than as a lead to primary sources. Workshop CLAUDE.md §7 rule 2 ("Aggregators and other textbooks are leads to primary sources, not primary sources themselves") is relaxed for the rewrite phase. Any factual claim that pushes beyond OpenStax — newer data, additional examples, contemporary AI/finance applications — carries `[verify]` and a primary-source citation.

## Voice notes

Workshop default — `feynman` plugin. Pedagogical, mechanism-first, hook with a genuine puzzle, hand judgment to the reader.

Voice anchor status: **voice-unanchored** at start of run. No `style/` samples exist at root or per-book. First several chapters serve as voice-setting; revision expected.

Adjustments for this book:

- **First-person discipline.** "I" used sparingly — finance pedagogy can drift into lecture-from-on-high. "We" preferred when working a calculation or unfolding a concept. "You" when handing a decision to the reader.
- **Mathematics on the page.** TVM, bond pricing, statistical reasoning — calculations get worked in the prose, not relegated to boxes. Numbers translate into decisions.
- **Specification before argument.** The book's job, repeatedly, is to pull apart vague terms — "risk," "return," "value," "capital," "efficient" — before letting them carry weight. Each of these words is doing several jobs at once in everyday usage.
- **Named cases over generic examples.** Bacon Signs (chapter 1), Peloton (chapter 1), Dow milestones — keep them. Add specific contemporary cases where OpenStax leans generic.
- **No corporate-finance triumphalism.** This is a textbook, not a recruitment brochure. The 2008 crisis, retirement-system shifts, the limits of financial models — named honestly.

## Prerequisites

College algebra. Basic accounting (debits, credits, income statement structure) helpful but the chapter on financial statements rebuilds the essentials.

## Course context

Designed to map onto a standard 14–15-week introductory finance syllabus. Twenty chapters allow for one chapter per week with two weeks for exam coverage in a 14-week course, or two chapters in some weeks for shorter terms.

## "With LLMs" layer — design

Two prompt types, both tied to **Claude** as primary tool. Adaptation notes for ChatGPT, Gemini, and other LLMs included.

- **Dig Deeper prompts** (inline, optional): 2–4 per chapter, marked `↳ Dig Deeper`. Invitations to explore a specific concept further with Claude. No deliverable. Skipping costs nothing.
- **LLM Exercises** (chapter-end, structured): one per chapter, advances a running project the learner builds across the whole book. Copy-paste ready. Designed to be adapted to the learner's domain, dataset, or hypothetical firm.

The running project will be selected from 3–5 candidates after all chapters are drafted. Likely candidates given the syllabus: a personal finance plan, a small-business financial model, an investment thesis on a chosen firm, a forecasting workbook for a chosen industry. Selection happens after Chapter Map.

## File conventions

- Chapter rewrites: `chapters/NN-slug.md` (matching the source subfolder name, *not* the workshop's `YYYY-MM-DD-` convention — deviation logged in `_notes.md`).
- Companions: `pantry/NN-slug.md`, `images/NN-slug.md`, `bookmaps/NN-slug.md`.
- Source subfolders (`chapters/NN-slug/`) are **not** auto-deleted after rewrite. Cleanup deferred to manual review.

---

*Initial version: 2026-05-08. Logged in `_notes.md`.*
