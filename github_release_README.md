# Attitude Sensing with Backscatter Arrays: Identifiability, Intrinsic Bounds, and Geometry Design — Full Version

Xuehui Dong, Kai Wan, Gui Zhou, Fuhai Wang, and Robert Caiming Qiu
School of Electronic Information and Communications, Huazhong University of Science and Technology, Wuhan, China

This repository hosts the **full version** of the manuscript submitted to the *IEEE Transactions on Signal Processing*. The full version contains the complete main text together with Appendices A–J, which collect the proofs of all lemmas, theorems, propositions, and corollaries. The submitted version omits the appendices for length and cites this document as *[Appendix X, N]*.

## Contents

| File | Description |
|---|---|
| `AttitudeSensing_BackscatterArrays_full.pdf` | Full version: main text, references, and Appendices A–J. |

## Appendix index

| Appendix | Proves |
|---|---|
| A | Lemma 2 (ambiguity set and null space) |
| B | Theorem 1 (observability threshold $d_u+d_b\ge5$) |
| C | Corollary 1 (degeneracy catalog) |
| D | Theorem 2 (intrinsic attitude FIM) |
| E | Proposition 2 (attitude information in phase differences) |
| F | Corollary 2 (two-pulse tangent-space CRB) |
| G | Proposition 3 (target-side spread law) |
| H | Proposition 4 (differencing topology) |
| I | Proposition 5 (optimal bistatic angle) |
| J | Proposition 1 (equivalent phase-domain noise covariance) |

## Abstract

Point-target sensing describes an object by range, angle, and Doppler, none of which reveals the object's attitude or angular velocity. A rigid body carrying a calibrated backscatter array encodes both states in its echo phases, which one illuminator and several mutually incoherent receive apertures can read. This paper develops the identifiability theory and the intrinsic performance limits of this encoding, and derives the geometry design laws that follow from both. The attitude enters every wrapped echo phase as a bilinear form between an aperture-side effective viewing direction and a target-side baseline, alongside translational, oscillator, and gain terms. With the viewing directions spanning $d_u$ dimensions and the baselines $d_b$, recovering an unconstrained attitude's nine entries needs $d_ud_b=9$, and we prove that the rotation constraint relaxes this to $d_u+d_b\ge5$, which is necessary and sufficient for identifiability and equivalent to a nonsingular Fisher information at every attitude. For geometries below this threshold, we provide a complete catalog of ambiguities. The Fisher information factors into an aperture-side matrix and the attitude-conjugated target-side spread, so the intrinsic Cramér–Rao bound depends on the attitude being estimated unless the spread is isotropic. One conjugate difference across antennas removes the three nuisance terms without loss of attitude information, and a grid search over the rotation group with integer least squares at every node resolves the ambiguities under a deterministic covering condition. The minimum spanning tree minimizes the integer search at a fixed baseline budget, and the worst-axis criterion is maximized at a bistatic angle of ninety degrees, with a closed-form ten-percent performance sector. Chip-level simulations confirm threshold, bounds, and design laws.

## How to cite

```bibtex
@misc{dong2026supplementary,
  author       = {Dong, Xuehui and Wan, Kai and Zhou, Gui and Wang, Fuhai and Qiu, Robert Caiming},
  title        = {Attitude sensing with backscatter arrays: Identifiability, intrinsic bounds, and geometry design (full version with appendices)},
  howpublished = {GitHub repository},
  year         = {2026},
  url          = {https://github.com/USERNAME/REPO}
}
```

## Status

Manuscript under review. The full version will be kept in sync with the submitted version; the commit history records every revision.

---

### Short description (for the GitHub repository "About" field, ≤350 characters)

Full version (with Appendices A–J: all proofs) of "Attitude Sensing with Backscatter Arrays: Identifiability, Intrinsic Bounds, and Geometry Design," submitted to IEEE Trans. Signal Process. Identifiability threshold d_u+d_b≥5, intrinsic CRB factorization, and geometry design laws for rigid-body attitude sensing with bistatic backscatter arrays.
