# Exact Finite-Level Mixing Geometry in Collatz Dynamics

**Hiroki Kamanoi**  
Draft — May 2026

This repository contains a research draft on exact finite-level mixing geometry for the accelerated Collatz/Syracuse map modulo powers of two.

The paper studies the Markov kernel induced on odd residue classes modulo `2^K` by Haar-random 2-adic lifts.

## Main Results

The paper proves:

- exact dyadic arithmetic-progression support geometry;
- an exact total variation formula;
- exact support-mixing time `T_mix(K)=K-1`;
- a normalized finite inverse-tree dual representation with a valuation-tail branch;
- a precise formulation of the remaining population-to-orbit obstruction.

## Important Clarification

This repository does **not** claim a proof of the Collatz conjecture.

It also does not claim:

- orbitwise ergodicity;
- convergence of all Collatz trajectories;
- a proved asymptotic spectral exponent;
- a proof of spectral rigidity.

The rigorous contribution is finite-level and population-level.

## Central Theme

The main distinction isolated in the paper is:

```text
support expansion != arithmetic decorrelation
```

The finite support geometry mixes exactly in total variation after `K-1` steps, but this does not automatically imply orbitwise decorrelation for a fixed positive integer trajectory.

## Numerical Component

The numerical spectral data are presented only as evidence. The apparent exponent near `0.39` is not claimed as a theorem.

## Files

- `collatz_mixing_paper.tex` — LaTeX source
- `collatz_mixing_paper.pdf` — compiled draft
- `REVIEW_NOTES.md` — mathematical and presentation notes
- `LICENSE` — MIT license

## Suggested arXiv Categories

Primary:

- `math.DS`

Secondary:

- `math.NT`
- `math.PR`

## Status

Research draft. Feedback welcome.
