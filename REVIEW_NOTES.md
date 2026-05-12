# REVIEW NOTES

## Critical Mathematical Correction

The original draft contained the statement:

> "v_2(3c+1) depends only on c mod 4"

This is false.

The correct statement is:

If

c ≡ c_0 mod 2^{v+1}

where

v = v_2(3c_0 + 1),

then

v_2(3c+1)=v.

This is the actual mechanism underlying the AP invariance lemma.

---

## Interpretation

This work establishes:

- exact finite-level support geometry,
- exact TV mixing,
- exact mixing time modulo powers of two.

It does NOT establish:

- orbitwise convergence,
- ergodicity of individual trajectories,
- a proof of the Collatz conjecture.

---

## Numerical Claims

The observed scaling:

δ_K ~ K^{-0.39}

is numerical only.

The paper should state:

"Numerical experiments are consistent with a power-law scaling."

rather than presenting the exponent as a theorem.

---

## Main Open Problem

The central unresolved issue is:

population mixing
≠
orbitwise decorrelation.

A divergent orbit, if it exists, would need to maintain coherent arithmetic
correlations across infinitely many scales simultaneously.

---

## Recommended Future Directions

- transfer operators,
- symbolic renewal systems,
- spectral analysis modulo 2^K,
- 2-adic harmonic analysis,
- arithmetic decorrelation,
- orbitwise lifting mechanisms.