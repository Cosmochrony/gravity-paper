This repository contains the source of the **Gravity 2.0A** Cosmochrony paper H  
[*Infrared Einstein Response from a Renormalized Spectral Entropy Functional*](pdf/Gravity.pdf).:

This work develops a minimal spectral framework in which:

- Newtonian 1/r behavior arises from resolvent structure in three dimensions
- The covariant four-dimensional extension yields an induced Einstein–Hilbert term
- The infrared-dominant local part of the renormalized metric variation is proportional to the Einstein tensor

The construction is purely operator-theoretic and spectral.
No fundamental gravitational dynamics are postulated.

## Core Result

For a minimal elliptic Laplace-type operator

A_g = -∇_g²

the renormalized spectral entropy functional

S_Π[g] = 1/2 log det' A_g

produces, in four dimensions:

- an induced Einstein tensor term from the a₂ heat-kernel pole
- quadratic curvature terms from a₄
- non-local form factors
- conformal anomaly contributions

In the weak-curvature regime R ℓ_χ² ≪ 1,
the two-derivative Einstein term dominates.

## Conceptual Structure

Gravity 2.0A integrates:

1. The 3D Newtonian resolvent mechanism (Gravity 1.0)
2. Heat-kernel expansion and Seeley–DeWitt structure
3. Zeta regularization and renormalization
4. Induced gravity interpretation (Sakharov mechanism)
5. Infrared derivative hierarchy

## Status

This framework is:

- elliptic and spectral
- renormalized
- infrared-controlled
- induced rather than fundamental

It does not assume:

- fundamental gravitational dynamics
- Lorentzian causal propagation
- strong-field or cosmological evolution

## Repository Structure
```
paper/
├── pdf/        # Compiled Gravity 1.0 PDF  
├── tex/        # LaTeX sources  
└── README.md
```
## Previous Version

Gravity 1.0 developed the three-dimensional Newtonian mechanism
without covariant extension.
Gravity 2.0A supersedes and integrates that analysis.

## Citation

If you reference this work, please cite:

> J. Beau, *Infrared Einstein Response from a Renormalized Spectral Entropy Functional*, Zenodo, 2026.

## Acknowledgements

Portions of the formal development, numerical validation, and editorial
refinement benefited from iterative interactions with large language models,
used as analytical assistants for testing internal consistency and exploring
alternative formulations.
All theoretical results and interpretations remain the sole responsibility
of the author.

## Contributions

This repository is intended as a research reference.

Critical feedback, mathematical scrutiny, and independent spectral analyses
are welcome.
Please open an issue to discuss conceptual points, technical details,
or possible extensions.
