This repository contains the source of the **Gravity 1.0** Cosmochrony paper H  
[*Newtonian Potentials from Projective Entropy in Three Dimensions*](pdf/Gravity.pdf).

This work develops a **minimal operator-theoretic framework** in which a
Newtonian \(1/r\) potential arises from the variation of a projective entropy
functional, without postulating a fundamental gravitational force law.

Starting from a positive elliptic Laplace-type operator in three spatial
dimensions, the framework shows how long-range Newtonian behavior follows
directly from resolvent structure and Green kernel asymptotics.

No dynamical gravitational equation is assumed.
The analysis is purely static and elliptic.

## Core Thesis

The paper is based on the following central statements:

1. **The Newtonian 1/r profile is dimensionally determined**  
   In three spatial dimensions, the Green function of a Laplace-type
   elliptic operator exhibits a universal \(1/r\) decay.
   This behavior is structural and does not depend on a specific force law.

2. **Projective entropy variation governs spatial response**  
   Defining  
   \[
   S_\Pi[A] = \tfrac12 \log \det{}' A,
   \]
   the first variation in the weak-perturbation regime reduces to
   \[
   \delta S_\Pi = \tfrac12 \mathrm{Tr}(A^{-1}\delta A),
   \]
   so that spatial structure is controlled entirely by the resolvent
   (Green kernel) of \(A\).

3. **Newtonian potentials arise as resolvent-mediated responses**  
   The entropy variation inherits the long-range \(1/r\) behavior
   of the Green function.
   The Newtonian potential appears as a static spectral response,
   not as a postulated interaction.

4. **The mechanism is purely elliptic and weak-field**  
   No Lorentzian structure, causal propagation, or relativistic
   dynamics are assumed.
   The analysis is restricted to small symmetric perturbations
   of a positive elliptic operator.

## Operator-Theoretic Framework

At the foundational level:

- the operator \(A\) is positive and elliptic
- it acts on a three-dimensional spatial domain
- the entropy functional is defined spectrally
- the variation is controlled by the resolvent \(A^{-1}\)

The long-range behavior emerges from:

- Green kernel asymptotics in three dimensions
- weak perturbation expansion
- first-order resolvent trace structure

The Newtonian profile is therefore a consequence of
dimension and ellipticity, not of a gravitational postulate.

## Numerical Verification

The mechanism is illustrated numerically using a discrete
three-dimensional Laplacian with localized symmetric perturbations.

The simulations confirm:

- validity of the first-order resolvent expansion
- emergence of the \(1/r\) Green profile
- existence of a finite spatial coherence threshold

Compact perturbations modify eigenvalues locally without
producing a macroscopic long-range shift, whereas sufficiently
extended perturbations induce a coherent Newtonian response.

This threshold reflects spectral projection structure,
not a dynamical screening mechanism.

## Dimensional Specificity

The \(1/r\) behavior is specific to three spatial dimensions.

In other dimensions, the Green kernel decays differently,
and the entropy variation would not reproduce a Newtonian profile.

The result is therefore dimensionally constrained and
not universal across arbitrary spatial dimension.

## Status of the Framework

This work is:

- **purely static and elliptic**
- **restricted to weak perturbations**
- **operator-theoretic and spectral**

It does **not** address:

- relativistic dynamics
- wave propagation
- gravitational radiation
- strong-field regimes
- covariant field equations

It **does** provide:

- a minimal derivation of the Newtonian \(1/r\) potential
  from spectral entropy variation
- a dimensionally grounded explanation of long-range behavior
- a bridge toward covariant generalization (developed separately)

## Repository Contents
```
paper/
├── pdf/        # Compiled Gravity 1.0 PDF  
├── tex/        # LaTeX sources  
├── figures/    # Diagrams and simulations  
└── README.md
```
## Links

- 📄 Paper PDF: https://github.com/Cosmochrony/gravity-paper/blob/main/pdf/Gravity.pdf
- 💻 GitHub organization: https://github.com/Cosmochrony

## Citation

If you reference this work, please cite:

> J. Beau, *Newtonian Potentials from Projective Entropy in Three Dimensions*, Zenodo, 2026.

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
