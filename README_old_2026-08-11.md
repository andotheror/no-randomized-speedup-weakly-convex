# No Randomized Speedup for Weakly Convex Optimization

## Abstract

For globally Lipschitz weakly convex optimization, the best known methods in the local value-and-subdifferential model need order $\varepsilon^{-4}$ queries to make the Moreau-envelope gradient at most $\varepsilon$. A recent lower bound proves that this rate is unavoidable for deterministic algorithms, even when every query returns the full subdifferential set. Whether randomization can improve the rate was left open. We prove that it cannot. Every randomized algorithm requires 

$$\Omega\\\\\\!\left( \frac{G^2\min\\\\\\{\rho\Delta,G^2\\\\\\}}{\varepsilon^4} \right)$$

 queries on the class of $G$-Lipschitz, $\rho$-weakly convex functions with initial gap at most $\Delta$. The oracle returns both the value and the entire subdifferential. The hard instances live in a polynomial dimension. When $\Delta\leq G^2/\rho$, the lower bound matches the known randomized upper bound in all four problem parameters. Two obstacles distinguish the result from a standard random rotation. A full subdifferential exposes any exact dependence on an unrevealed direction, and unbounded queries defeat concentration. We give the diagonal chain a smooth dead zone that yields exact local independence. We then combine a smooth soft projection with a linear-growth radial penalty. This wrapper is globally Lipschitz, preserves weak convexity, hides unbounded queries, and introduces no spurious Moreau-stationary point. A conditional-Haar argument completes the randomized lower bound.

## Contributions

Our main theorem closes the randomized local-oracle complexity in the small-gap
regime $\Delta\leq G^2/\rho$. It matches both the deterministic lower bound
and the known randomized upper bound, including the dependence on
$G,\rho,\Delta$, and $\varepsilon$. The proof also gives a reusable globally Lipschitz
replacement for the quadratic soft-projection wrapper in randomized
stationarity lower bounds. Finally, we formulate a robust full-set chain
condition and show that a width-six diagonal filtration is compatible with the
conditional-Haar argument of.

## Keywords

weakly convex optimization, oracle complexity, randomized algorithms, lower bounds, Moreau envelope, nonsmooth optimization

## Files

- `main.pdf`, `supplement.pdf`
- `main.tex`, `supplement.tex`
- `references.bib`
- `aistats2027.sty`, `fancyhdr.sty`
- `main.pdf.ots`, `supplement.pdf.ots`, `README.md.ots` OpenTimestamps priority proofs
