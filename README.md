# APM1110-FA8

**Course:** APM1110: Probability and Probability Distributions
**Assessment:** Formative Assessment 8 (30 points)
**Author:** Arvin

This repository has my solutions to Formative Assessment 8. I solved each problem by hand with full steps, and I used R to check my answers.

## Files

| File | Description |
|------|-------------|
| `APM1110-FA8.Rmd` | R Markdown source with all solutions, formulas, and R code |
| `APM1110-FA8.pdf` | Knitted PDF of the full solutions |
| `README.md` | This file |

## Topics Covered

1. **Problem 1 (6 pts):** Urn problem with a randomly chosen color, using the law of total probability and indicator variables.
2. **Problem 2 (8 pts):** Yule-Simon distribution. I showed it is a valid PMF, that E[X] = 2, and that E[X²] is infinite.
3. **Problem 3 (4 pts):** Finding the constants a and b of a density from its mean.
4. **Problem 4 (4 pts):** Mean and variance of a standardized random variable.
5. **Problem 5 (8 pts):** Sum of independent Poisson variables using moment generating functions.

## Final Answers

| Item | Answer |
|------|--------|
| 1(a) | P(X = 0) = 6805/37950 ≈ 0.1793 |
| 1(b) | P(Xᵢ = 1) = 1/3 for i = 1, 2, 3, 4 |
| 1(c) | E[X] = 4/3 ≈ 1.3333 |
| 2(a) | The probabilities sum to 1 (telescoping series) |
| 2(b) | E[X] = 2 |
| 2(c) | E[X²] = ∞ (compared with the harmonic series) |
| 3 | a = 3/5 = 0.6000, b = 6/5 = 1.2000 |
| 4 | E[Y] = 0, Var(Y) = 1 |
| 5(a) | M_W(t) = exp(5(eᵗ − 1)) |
| 5(b) | W ~ Poisson(5) |
| 5(c) | E[W] = 5, E[W²] = 30 |

