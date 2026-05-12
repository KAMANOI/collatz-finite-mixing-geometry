# Review Notes

## Review-Safety Revisions Included

This version includes several changes intended to improve mathematical and referee robustness.

### 1. AP invariance corrected

The earlier dangerous statement that `v_2(3c+1)` is determined by `c mod 4` has been removed.

The corrected local statement is:

```text
If c ≡ c_0 mod 2^{v+1}, where v=v_2(3c_0+1), then v_2(3c+1)=v.
```

This is the correct mechanism behind arithmetic-progression invariance.

### 2. Finite valuation tail handled

At finite level `K`, valuation levels `v >= K` must be aggregated into a tail branch.

The dual representation is therefore normalized as:

```text
sum_{v=1}^{K-1} 2^{-v} f(T_K^{-v}(b))
+ 2^{-(K-1)} f(T_K^{- >= K}(b)).
```

This avoids the incorrect finite sum `sum_{v=1}^K 2^{-v}`, which does not have the correct stochastic interpretation.

### 3. Spectral claims weakened

The exponent near `0.39` is described only as numerical evidence.

The paper no longer presents this exponent as theoretically established.

### 4. Collatz-conjecture claims restricted

The paper explicitly says that it does not prove the Collatz conjecture.

The remaining obstruction is stated as the population-to-orbit gap.

## Remaining Open Problems

- sharp spectral or singular-value estimates for `P_K`;
- spectral theory of the limiting 2-adic transfer operator;
- orbitwise arithmetic decorrelation;
- any rigorous bridge from finite-level population mixing to individual Collatz trajectories.

## Recommended Repository Positioning

Use:

```text
Exact finite-level mixing geometry in accelerated Collatz dynamics.
```

Avoid:

```text
Proof of Collatz
Complete resolution
Collatz solved
```
