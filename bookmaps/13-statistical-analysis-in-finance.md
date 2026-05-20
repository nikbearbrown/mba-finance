# Source map — Chapter 13

## Source files

| File | Module | OpenStax section |
|---|---|---|
| `01-m00077.md` | m00077 | Intro |
| `02-m00078.md` | m00078 | Measures of center |
| `03-m00079.md` | m00079 | Measures of spread |
| `04-m00080.md` | m00080 | Probability/distributions |
| `05-m00081.md` | m00081 | Normal distribution |
| `06-m00082.md` | m00082 | Sharpe ratio / risk-adjusted return |
| `07-m00083.md` | m00083 | Excel applications |
| `08-m00084.md` | m00084 | (CFA reference / additional) |

(Module structure inferred from file order; subagent summary was over the context limit and was used in compressed form.)

## Section-level mapping

### Hook — *Single-year return puzzle*
- **Source:** None directly. Workshop construction.
- **Treatment:** Sets up why we need statistics on a sample, not just a single observation.

### Concept 1 — *Measures of center*
- **Source:** m00078.
- **Treatment:** Standard treatment of arithmetic vs. geometric mean. **Volatility drag formula** (geometric ≈ arithmetic - σ²/2) is workshop emphasis; well-known but often understated.

### Concept 2 — *Measures of spread*
- **Source:** m00079, m00081.
- **Treatment:** Standard variance/std-dev derivation. Normal distribution properties preserved. **Fat-tails / non-normality** discussion is workshop addition; OpenStax tends to underemphasize.

### Concept 3 — *Relationships and Sharpe*
- **Source:** m00080 (covariance/correlation), m00082 (Sharpe).
- **Treatment:** Standard correlation treatment. Portfolio variance formula derived. Sharpe ratio defined and applied. **Modern Portfolio Theory mention** (Markowitz 1952) is workshop forward-link to Ch 15.

## Verification flags
- All numerical worked examples self-consistent and computable.
- `[verify]` Real-world correlation values (US stocks vs. bonds, etc.) for current data.
- `[verify]` Long-run S&P 500 Sharpe ~0.4.
- `[verify]` 1987, 1998, 2008, 2020 specific tail-event dates.

## Voice-anchor status
Chapter 13 of run. Statistics chapter; relatively short prose, math density appropriate. Voice consistent.

Note: subagent source summary exceeded chat context limit; chapter written from preview + standard finance pedagogy + verified formulas. Bookmap honest about this.
