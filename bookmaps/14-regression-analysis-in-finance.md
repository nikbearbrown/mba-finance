# Source map — Chapter 14

## Source files

| File | Module | OpenStax section |
|---|---|---|
| `01-m00085.md` | m00085 | Intro |
| `02-m00086.md` | m00086 | Correlation |
| `03-m00087.md` | m00087 | Least squares & residuals |
| `04-m00089.md` | m00089 | Slope and intercept (technology) |
| `05-m00090.md` | m00090 | Regression in financial forecasting (beta) |
| `06-m00091.md` | m00091 | Prediction & intervals |
| `07-m00132.md` | m00132 | R statistical tool |

## Section-level mapping

### Hook — *Two stocks at same return*
- **Source:** None directly. Workshop construction.
- **Treatment:** Frames the chapter as the answer to *why same-return stocks command different valuations.*

### Concept 1 — *Correlation and regression machinery*
- **Source:** m00086, m00087, m00089.
- **Treatment:** All formulas preserved. Standard OLS treatment. R² formal definition is workshop addition (the source's Module 7 mentions it in R output but doesn't define).

### Concept 2 — *Beta and CAPM*
- **Source:** m00090.
- **Treatment:** Beta as regression slope preserved. **CAPM is workshop addition** — OpenStax modules don't develop CAPM explicitly, treating beta as a stand-alone slope rather than connecting it to the security market line. Workshop adds the standard CAPM equation, SML, and cost-of-equity computation because they're essential for Ch 17 and the project.

### Concept 3 — *Building cost of equity for the project*
- **Source:** None directly. Workshop construction.
- **Treatment:** Step-by-step practitioner workflow. Sensitivity analysis emphasized.

## Deferred from source
- **Detailed prediction interval mechanics** (m00091) — covered briefly; full treatment is intermediate statistics.
- **R statistical tool detailed walkthrough** (m00132) — workshop reduces to a couple of code lines.
- **Multiple regression beyond brief mention** — saved for advanced courses.

## Verification flags
- `[verify]` Nike beta 0.83 (OpenStax data; vintage-specific).
- `[verify]` Sample beta values for Apple (1.2), Tesla (2.0), Walmart (0.5), P&G (0.4).
- `[verify]` ERP estimate range 4-6%.
- `[verify]` Significance threshold rule $|r| \geq 2/\sqrt{n}$.

## Voice-anchor status
Chapter 14. Voice consistent. Workshop adds CAPM proper because OpenStax leaves it implicit; this is a defensible deviation given the chapter's role in the project.
