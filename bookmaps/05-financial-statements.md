# Source map — Chapter 5: Financial Statements

## Source files

| File | Module | OpenStax section | Notes |
|---|---|---|---|
| `01-m00030.md` | m00030 | Intro / Clear Lake | Setup module |
| `02-m00031.md` | m00031 | Income Statement | Income statement structure |
| `03-m00032.md` | m00032 | Balance Sheet | Balance sheet structure + limitations |
| `04-m00033.md` | m00033 | Connections IS↔BS | Retained earnings link |
| `05-m00034.md` | m00034 | Statement of Equity | Equity components, dividend types |
| `06-m00035.md` | m00035 | Cash Flow Statement | Three sections, indirect method |
| `07-m00036.md` | m00036 | Operating & Free CF | OCF and FCF formulas |
| `08-m00037.md` | m00037 | Common-Size Statements | Vertical analysis |
| `09-m00038.md` | m00038 | Reporting Requirements | 10-K, 10-Q, fiscal vs. calendar year |

## Section-level mapping

### Hook — *The $100M factory across three statements*
- **Source:** None directly. Workshop construction.
- **Treatment:** Chosen because it's a clean way to demonstrate the integrated nature of the statement system from the first paragraph. Replaces OpenStax's straightforward "intro to four statements" framing.

### Concept 1 — *The four statements*
- **Source:** m00031 (income statement), m00032 (balance sheet), m00034 (statement of equity), m00035 (cash flow statement).
- **Treatment:** All four statements covered with their structures preserved from OpenStax. Apple specifics from m00031, m00032 — fiscal 2020 figures preserved (with `[verify]` flags for currency).
- **Buffett EBITDA criticism** is workshop addition (well-known, attributable to multiple Berkshire shareholder letters).
- **Balance sheet limitations** (historical cost, estimates, point-in-time, missing intangibles) — preserved from m00032.

### Concept 2 — *Connecting the statements*
- **Source:** m00033 (the connections module). m00034 (statement of equity flow).
- **Treatment:** The "retained earnings link" and "cash link" framing is workshop framing. OpenStax presents the connections without naming them as named links.
- **Expenses-vs-payables example:** preserved from m00033 verbatim.
- **Apple buyback worked example:** workshop construction (Apple does buy back stock at scale; specific transactions are illustrative).

### Concept 3 — *Common-size analysis*
- **Source:** m00037 (vertical analysis); m00036 (OCF and FCF).
- **Treatment:** Direct rewrite. Clear Lake vs. Charlie's example preserved from m00037. Apple-vs-competitor common-size comparison is workshop construction (illustrative figures consistent with Apple's actual structure).
- **OCF and FCF formulas:** preserved from m00036.

### Synthesis & Forward Links
- Workshop construction. Set up downstream chapters.

### Exercises
- 5.1–5.3 warm-up: from chapter content.
- 5.4 application: cash flow statement drill (workshop-constructed numbers).
- 5.5 application: common-size construction (workshop-constructed firms).
- 5.6 application: project-aware (real 10-K work).
- 5.7 synthesis: net-income-vs-cash divergence diagnostic. Workshop construction.
- 5.8 synthesis: Apple cash pile question. Workshop construction.
- 5.9 challenge: receivables-as-percent-of-revenue diagnostic. Workshop construction.
- 5.10 challenge: project-extending.

## Deferred from source

- **m00038 (Reporting Requirements)** — covered briefly in Ch 2 (corporate disclosure); folded as a brief mention in Ch 5 synthesis. Detailed treatment is redundant with Ch 2.
- **Statement of Retained Earnings as standalone** — OpenStax separates this from Statement of Stockholders' Equity in some places. Workshop merges them as one statement with a retained earnings sub-section.
- **Cash dividend / stock dividend / property dividend distinction** — preserved in pantry; not all three flavors needed in main prose.

## Verification flags
- `[verify]` Apple fiscal 2020: net income $57.4B, revenue $274.5B, EBITDA ~$109B.
- `[verify]` Apple fiscal 2020: total assets $323.9B, total liab+equity matches.
- `[verify]` Apple's marketable securities + cash ~$191B (fiscal 2020).
- `[verify]` Buffett's EBITDA criticism quotes (multiple Berkshire letters; check exact phrasing).
- `[verify]` Common-size percentages used in concept 3 against actual data when published.

## Voice-anchor status
Chapter 5 of run. Voice anchored. Pedagogical pattern consistent. Voice can be considered stable through the rest of the book.
