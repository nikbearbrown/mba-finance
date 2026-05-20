# Source map — Chapter 8: TVM II — Annuities

## Source files

| File | Module | OpenStax section |
|---|---|---|
| `01-m00051.md` | m00051 | Why it matters / income vs. wealth |
| `02-m00052.md` | m00052 | Perpetuities |
| `03-m00053.md` | m00053 | Annuities, structured settlements, retirement |
| `04-m00054.md` | m00054 | Loans and amortization |
| `05-m00055.md` | m00055 | Stated vs. effective rates |
| `06-m00056.md` | m00056 | Calculator and Excel mechanics |

## Section-level mapping

### Hook — *Lottery puzzle*
- **Source:** m00053 (lottery example).
- **Treatment:** Workshop reframes as the chapter-opening puzzle; OpenStax used it inline.

### Concept 1 — *Perpetuities*
- **Source:** m00052.
- **Treatment:** Direct rewrite. Geometric-series derivation is workshop addition (m00052 presents formulas without derivation). Shaw / Rooney examples preserved.

### Concept 2 — *Annuities*
- **Source:** m00053.
- **Treatment:** All formulas preserved. Lottery / structured settlement / retirement examples preserved. Two-workers comparison from m00051/m00053 preserved with workshop framing.

### Concept 3 — *Real-world applications*
- **Source:** m00054 (amortization), m00055 (effective rates).
- **Treatment:** Loan amortization preserved. Mortgage example preserved. Payday loan example preserved with workshop EAR computation (3,370%, more pointed than source's nominal 364%).

### Calculator/Excel mechanics
- **Source:** m00056.
- **Treatment:** Compressed. Excel functions preserved (`=PV`, `=FV`, `=PMT`, `=EFFECT`); BA II Plus calculator steps deferred.

## Deferred from source
- **Detailed calculator step-by-step** (m00056) — most students will use Excel.
- **Refund Anticipation Loan** (m00055) — preserved in the workshop's payday-loan example treatment.
- **Income vs. wealth** quote from *Millionaire Next Door* — preserved in pantry, not in main prose.

## Verification flags
- `[verify]` Two-workers calculation precise figures.
- `[verify]` $32,000 / 36-month / 6% loan amortization detail (Year 12, Year 24 balances).
- `[verify]` $140,000 / 20-year / 3.6% mortgage figures.
- `[verify]` Payday loan EAR calculation (3,370% claim).

## Voice-anchor status
Chapter 8 of run. Voice consistent. Math density similar to Ch 7. Both chapters relatively short by design.
