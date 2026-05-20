# Source map — Chapter 7: TVM I

## Source files

| File | Module | OpenStax section |
|---|---|---|
| `01-m00046.md` | m00046 | Intro to TVM |
| `02-m00047.md` | m00047 | Why time affects money / lump sum |
| `03-m00048.md` | m00048 | FV and compounding |
| `04-m00049.md` | m00049 | FV/PV with calc & Excel |
| `05-m00050.md` | m00050 | PV, inflation, compounding frequency, Fisher, Rule of 72 |

## Section-level mapping

### Hook — *Two-offer puzzle*
- **Source:** None directly. Workshop construction.
- **Treatment:** Replaces OpenStax's gentle intro with a sharper puzzle that surfaces the breakeven concept.

### Concept 1 — *Why money has time value*
- **Source:** m00046, m00047, m00048.
- **Treatment:** Three reasons preserved from m00046. Master formula derived in workshop voice. Two-friends example is workshop construction (well-known illustration in personal finance literature).
- **$1,000 at 4% over 3/10/50 years table** preserved verbatim from m00048.

### Concept 2 — *Four directions*
- **Source:** m00049 (calc/Excel mechanics).
- **Treatment:** Four-directions framing is workshop reorganization. OpenStax presents them sequentially without the unifying frame. All formulas and worked examples preserved from m00049.
- **Apple worked example** is workshop addition tying to the running project.

### Concept 3 — *Refinements*
- **Source:** m00050 (compounding frequency, Fisher, Rule of 72).
- **Treatment:** Direct rewrite. **Continuous compounding formula** ($FV = PV \cdot e^{rn}$) is workshop addition — OpenStax m00050 mentions but does not show the formula. Workshop adds it for completeness and for use in Ch 20.
- **Fisher equation** preserved from m00050.
- **Rule of 72** preserved with applications to GDP, inflation, credit cards, population.

## Deferred from source
- **Melvin examples (m00048)** — generic personal-finance examples; cut for length.
- **Detailed calculator mechanics** — OpenStax has step-by-step calculator instructions for the BA II Plus. Workshop reduces these to "Excel does this with =FV/=PV/=RATE/=NPER" because most students will use Excel/Sheets, not a financial calculator.
- **Inflation discussion in m00050** — duplicates Ch 3 content; condensed in workshop.

## Verification flags
- `[verify]` Two-friends arithmetic ($45K → $887K vs. $175K → $861K).
- `[verify]` House appreciation $400K at 4% for 6 years = $506,128.
- `[verify]` All compounding-frequency examples (especially $1 at 3% for 100 years).

## Voice-anchor status
Chapter 7. Voice anchored. First math-heavy chapter; voice adapted appropriately — formulas first, prose around them. Subsequent TVM chapters (8, 9) follow same pattern.
