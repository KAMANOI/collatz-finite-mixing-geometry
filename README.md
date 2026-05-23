# Exact Finite-Level Mixing Geometry in Accelerated Collatz Dynamics

**Hiroki Kamanoi**  
Draft — May 2026

Paper B in a series on Collatz dynamics through finite Markov chain theory.

## Overview

This paper establishes the exact finite-level mixing geometry for the accelerated Collatz map modulo $2^K$.

The central result is an exact arithmetic progression support geometry and an exact total variation formula for the Haar kernel. The paper isolates a fundamental separation between population-level geometric mixing and individual orbit arithmetic decorrelation.

## Main Results

The paper establishes:

- exact arithmetic progression support geometry for the Haar kernel $P_K^{\mathrm{Haar}}$;
- exact total variation formula for $P_K^{\mathrm{Haar}}$;
- exact mixing time:

  $$T_\mathrm{mix}(K) = K - 1$$

- dual inverse-tree representation;
- distinction between exact Haar kernels and lift-averaged empirical kernels $P_{K,M}$.

## Important Clarification

This repository does **not** claim a proof of the Collatz conjecture.

It also does not claim:

- orbitwise ergodicity or arithmetic decorrelation;
- asymptotic spectral rigidity.

The exact finite-level support geometry is proved rigorously for the Haar kernel. Numerical spectral observations concern lift-averaged empirical kernels $P_{K,M}$ and are not theorems.

## Logical Structure of the Series

| Paper | Core result | Status |
|-------|-------------|--------|
| A | Exact operator structure and renewal systems | Proved |
| **B (this paper)** | Exact TV mixing: $T_\mathrm{mix}(K) = K-1$ | Proved |
| C | One-bit spectral jump $\delta_{K,1} \approx 0.29$; Open Gap Problem | Numerical / Open |
| D | Simultaneous scale coherence; conditional diverging mixing | Open / Conditional |

## Files

- `collatz_mixing_paper.tex` — LaTeX source
- `collatz_mixing_paper.pdf` — compiled draft
- `REVIEW_NOTES.md` — critical notes on the kernel distinction

## Suggested arXiv Categories

Primary: `math.DS`  
Secondary: `math.NT`, `math.PR`

## License

MIT License


---

## Related work

This repository is part of a series on Collatz dynamics:

| Repository | Description |
|------------|-------------|
| [collatz-renewal-structure](https://github.com/KAMANOI/collatz-renewal-structure) | Paper A: exact renewal structure and operator theory |
| [collatz-finite-mixing-geometry](https://github.com/KAMANOI/collatz-finite-mixing-geometry) | Finite-level mixing geometry |
| [collatz-spectral-amplification](https://github.com/KAMANOI/collatz-spectral-amplification) | Paper C: spectral amplification |
| [collatz-scale-coherence](https://github.com/KAMANOI/collatz-scale-coherence) | Paper D: scale-coherence rigidity |

## Author

Hiroki Kamanoi  
hirokikamanoi@gmail.com  
https://github.com/KAMANOI