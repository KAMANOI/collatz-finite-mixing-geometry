# Exact Finite-Level Mixing Geometry in Collatz Dynamics

**Hiroki Kamanoi**  
Draft — May 2026

## Overview

This repository studies finite-level mixing properties of the accelerated Collatz
(Syracuse) map modulo powers of two.

The main result is an exact description of the support geometry of the induced
Markov kernel on odd residue classes modulo `2^K`.

The paper proves:

- exact arithmetic progression support geometry,
- an exact total variation formula,
- exact mixing time:

  `T_mix(K) = K - 1`

- and a separation between:
  - support-based TV mixing,
  - spectral/correlation mixing.

This repository does **not** claim a proof of the Collatz conjecture.

Instead, the paper isolates a precise obstruction:

> finite-level mixing is exact, but orbitwise lifting remains open.

---

## Main Result

For every `K ≥ 2`, every odd residue class `a mod 2^K`,
and every `t < K`,

the support of

`P_K^t(a, ·)`

is exactly a dyadic arithmetic progression with:

- spacing:

  `2^{K-S_t(a)}`

- cardinality:

  `2^{S_t(a)}`

where

`S_t(a)=Σ_{s≤t} v_2(3F_K^{s-1}(a)+1)`.

Mixing occurs precisely when the progression fills all odd residue classes.

---

## Main Themes

The paper distinguishes two different notions of randomness:

1. Geometric support mixing
2. Arithmetic decorrelation

The key phenomenon is:

support expansion ≠ decorrelation.

---

## Important Clarification

The repository does NOT claim:

- a proof of the Collatz conjecture,
- orbitwise ergodicity,
- asymptotic spectral rigidity,
- convergence of all trajectories.

The results concern exact finite-level geometry modulo powers of two.

---

## Repository Contents

- `collatz_mixing_paper.tex`
- `collatz_mixing_paper.pdf`
- `README.md`
- `REVIEW_NOTES.md`
- `LICENSE`

---

## arXiv Categories

Primary:
- math.DS

Secondary:
- math.NT
- math.PR

---

## License

MIT License