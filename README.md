This repository contains the source of the **O29 Cosmochrony paper**  
*Spin-1/2 Sector Identification via the Symmetric Rank Formula:
Effective Dimension of the Admissible Covariance in End(Vρ)*.

This work extends the **spectral admissibility sub-programme** by resolving
the representation-theoretic identification problem left open in **O26–O28**.

It addresses the next structural question after **O28**:

> Why does the effective covariance rank equal 3 instead of 4,
> and what is the correct observable for representation identification?

## Quick Summary

The observed rank deficit is not a numerical artefact.

It is a structural constraint.

More precisely:

- conjugate-pair data are constrained by an anti-linear parity
- this forces outer products into a symmetric subspace
- the accessible rank is reduced from $d_\rho^2$ to $d_\rho(d_\rho+1)/2$

Thus:

- the observable used in O26 must be reformulated
- the corrected observable uniquely identifies $d_\rho = 2$

This confirms the **spin-$\tfrac{1}{2}$** sector.

## Context

**O26–O28** established that:

- σpair behaves as a quadratic observable (**O26**)
- a representation-theoretic sector is required (Level III)
- the effective covariance rank should test the sector dimension
- the proxy computation in End($H_{\mathrm{eff}}$) yields:
  $r_{\mathrm{eff}} = 3$
  instead of the expected:
  $d_\rho^2 = 4$

However:

- the origin of this discrepancy was unclear
- it was attributed to a possible projection artefact
- the correct observable space was not identified

This defines the scope of **O29**.

## Core Result

The paper establishes that:

> The covariance built from conjugate-pair data is intrinsically confined to
> the symmetric subspace $\mathrm{Sym}(V_\rho, \mathbb{C})$,
> due to the anti-linear Born–Infeld parity constraint.

As a consequence:

$r_{\mathrm{eff}} = \frac{d_\rho(d_\rho+1)}{2}$

This replaces the O26 target:

$d_\rho^2 \;\longrightarrow\; \frac{d_\rho(d_\rho+1)}{2}$

## Main Structural Results

### 1. Symmetric constraint on outer products

*Result.* For all admissible trajectories:

$M_j = w_j \otimes w_j^\top \in \mathrm{Sym}(V_\rho, \mathbb{C})$

Thus:

- the observable does not explore $\mathrm{End}(V_\rho)$
- it is confined to the symmetric subspace

This constraint is:

- algebraic (pointwise)
- independent of averaging
- invariant under admissible transformations

### 2. Origin of the constraint

*Result.* The restriction arises from:

- anti-linear Born–Infeld parity:
  $\pi_{q-c}(v) = \pi_c(v)$
  (up to a slowly varying phase)

Thus:

- conjugate blocks are not independent
- the observable is structurally constrained

### 3. Symmetric rank formula

*Result.*

$r_{\mathrm{eff}} = \frac{d_\rho(d_\rho+1)}{2}$

Thus:

- rank is reduced relative to the full matrix space
- the reduction is intrinsic to the data

### 4. Unique sector identification

*Result.* Inverting the rank formula:

$d_\rho = \frac{-1 + \sqrt{1 + 8 r_{\mathrm{eff}}}}{2}$

For:

$r_{\mathrm{eff}} = 3 \;\Rightarrow\; d_\rho = 2$

Thus:

- the spin-$\tfrac{1}{2}$ sector is uniquely identified
- no ambiguity remains

### 5. Reformulation of O26 Criterion

*Result.* The correct falsifiability condition becomes:

- not $r_{\mathrm{eff}} = d_\rho^2$
- but:
  $r_{\mathrm{eff}} = \frac{d_\rho(d_\rho+1)}{2}$

Thus:

- O26 Level III is preserved
- the observable is correctly specified

## Numerical Results

The computation confirms:

- $r_{\mathrm{eff}} = 3$ across all pairs
- zero inter-pair variance at $q = 61, 151$
- modal consistency at $q = 101$ (multi-sample confirmed)

Additional observations:

- eigenvalue structure:
  $[1 : \tfrac{1}{2} : \tfrac{1}{2}]$
- symmetry ratio small but non-zero:
  $\|M - M^\top\| / \|M\| \sim 10^{-2}$

Thus:

- symmetry is structural but phase-modulated
- rank result is robust

## Foundational Chain from the Substrate

The derivation is fully internal:

Born–Infeld admissibility  
$\to$ pair observable (**O16–O21**)  
$\to$ projection locking (**O22**)  
$\to$ conditional rank-three carrier (**O23** Theorem 3.1, supplied spinor carrier)  
$\to$ rank stability (**O24**)  
$\to$ numerical validation (**O25**)  
$\to$ quadratic structure (**O26**)  
$\to$ representation constraint (**O27**)  
$\to$ observable correction and sector identification (**O29**)

No external structure is imposed.

## Mathematical Role of O29

**O29** provides the structural resolution of the representation problem:

- explains the rank discrepancy observed in O28
- identifies the correct observable space ($\mathrm{Sym}(V_\rho)$)
- derives the symmetric rank formula
- enables unique sector identification
- reformulates the O26 falsifiability criterion

More precisely, the paper:

- proves the symmetric constraint
- derives the rank formula
- validates the result numerically
- closes the representation identification loop

## Epistemic Structure of the Paper

### Established input

- quadratic observable (**O26**)
- admissible morphism structure (**O27**)
- numerical rank observation (**O28**)

### New results

- symmetric constraint (proved)
- symmetric rank formula (proved)
- inversion for $d_\rho$ (analytic)
- corrected falsifiability criterion
- numerical confirmation across primes

### Remaining open problems

- analytical proof of $\dim V_\rho = 2$
- extension to larger primes
- full $d_\rho^2$ measurement via independent blocks
- analytical derivation of eigenvalue ratios

## Interpretation of the Result

The conceptual shift is:

- previous view: observable explores full matrix space
- O29: observable is **structurally restricted**

Thus:

- the rank deficit is not an error
- it is a **signature of admissibility constraints**
- representation identification requires the correct observable

## Structural Role of O29

**O29** completes the representation identification stage:

- **O26**: quadratic structure
- **O27**: SU(2) rigidity
- **O28**: numerical rank observation
- **O29**: structural explanation + identification

Thus:

- the observable is corrected
- the sector is identified
- the chain is closed

## What O29 Adds

- identification of the correct observable space
- symmetric constraint from parity
- symmetric rank formula
- unique determination of $d_\rho$
- resolution of the O28 discrepancy
- completion of Level III identification

## Outcome

The spectral admissibility framework is now:

- structurally grounded (**O24**)
- numerically validated (**O25**)
- geometrically interpreted (**O26**)
- representation-theoretically constrained (**O27**)
- observationally resolved (**O29**)

The sector is:

- uniquely identified
- structurally justified
- numerically confirmed

## Residual Open Problems

### Full-rank observable

Design a protocol probing $d_\rho^2$.

### Analytical dimension proof

Derive $\dim V_\rho = 2$ from admissibility.

### Large-q regime

Confirm stability for larger primes.

### Eigenvalue structure

Derive $[1 : 1/2 : 1/2]$ analytically.

### Representation embedding

Construct explicit embedding into $V_\rho$.

## Status

The programme is now:

- structurally closed (**O24**)
- numerically validated (**O25**)
- geometrically lifted (**O26**)
- representation-constrained (**O27**)
- observationally completed (**O29**)

## Repository Structure

```text
paper/
├── out/      # Compiled O29 PDF
├── tex/      # LaTeX sources
└── README.md
```
# Citation

If you reference this work, please cite:

J. Beau
Spin-1/2 Sector Identification via the Symmetric Rank Formula:
Effective Dimension of the Admissible Covariance in End(Vρ)
Zenodo, 2026.

# Acknowledgements

Portions of the derivations, conceptual synthesis, structural organisation,
and editorial refinement benefited from iterative interactions with large
language models used as analytical assistants.

All theoretical results, computations, and interpretations remain the sole
responsibility of the author.

# Contributions

This repository is intended as a research reference.

Critical feedback, independent verification, and further analysis of:

- admissible covariance structures
- symmetric constraints
- representation identification
- sector selection
- measurement observables

are welcome.

Please open an issue to discuss conceptual points, technical details, or
possible extensions.
