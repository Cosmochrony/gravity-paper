# Conditions for an Infrared Einstein Sector from Spectral Geometry

This repository contains the source of the Cosmochrony Gravity paper.

Version 3.3 separates two regularization statements that previous versions conflated:

- a physical proper-time cutoff produces power-sensitive local terms;
- zeta regularization controls the finite determinant and logarithmic scale dependence.

## Spectral input

For a four-dimensional minimal scalar Laplacian,

\[
\operatorname{Tr}(e^{-tA_g})
\sim
\frac{1}{(4\pi t)^2}
\int_M \mathrm d^4x\,\sqrt g\,
\left(a_0+t a_2+t^2a_4+\cdots\right),
\]

with

\[
a_0=1,
\qquad
a_2=\frac{R}{6},
\]

and

\[
a_4=\frac{1}{360}
\left(
12\nabla^2R+5R^2-2R_{\mu\nu}R^{\mu\nu}
+2R_{\mu\nu\rho\sigma}R^{\mu\nu\rho\sigma}
\right).
\]

The factor \((4\pi t)^{-2}\) is outside the coefficient series and is not repeated
inside \(a_4\).

## Separation of schemes

With the proper-time cutoff \(\Lambda=\ell_{\mathrm{sp}}^{-1}\),

\[
S_{\Pi,\mathrm{loc}}^\Lambda
=-rac{1}{2(4\pi)^2}
\int_M\mathrm d^4x\,\sqrt g
\left[
\frac{\Lambda^4}{2}a_0
+\Lambda^2a_2
+\log\!\left(\frac{\Lambda^2}{\mu^2}\right)a_4
\right].
\]

For \(S_\Pi=+\tfrac12\log\det' A_g\), one minimal scalar therefore contributes

\[
\Delta c_{\mathrm{EH}}^\Lambda
=-\frac{\Lambda^2}{12(4\pi)^2}.
\]

Zeta regularization gives instead

\[
\frac{\mathrm d S_\Pi^\zeta}{\mathrm d\log\mu}
=-\zeta_A(0),
\]

which is governed in four dimensions by the integrated \(a_4\) coefficient.
It does not produce an \(a_2\mu^2R\) term.

## Conditional Einstein sector

The renormalized metric variation may contain

\[
\delta S_\Pi^{\mathrm{ren}}
=\int_M\mathrm d^4x\,\sqrt g
\left[
c_{\mathrm{EH}}^{\mathrm{ren}}G_{\mu\nu}
+c_\Lambda^{\mathrm{ren}}g_{\mu\nu}
+\beta^{\mathrm{ren}}B_{\mu\nu}
+\cdots
\right]\delta g^{\mu\nu}.
\]

The observed coupling is defined by the matching condition

\[
c_{\mathrm{EH}}^{\mathrm{ren}}=\frac{1}{16\pi G_N}.
\]

The heat-kernel expansion determines the cutoff-sensitive contribution but not the
finite value or sign of this coefficient.
Additional operator content and a renormalization condition are required to obtain the
observed positive Newton constant.

The local Einstein term dominates the four-derivative sector when

\[
RL_4^2\ll1,
\qquad
L_4^2=left|\frac{\beta^{\mathrm{ren}}}{c_{\mathrm{EH}}^{\mathrm{ren}}}\right|.
\]

Under cutoff-dominated matching without cancellations,
\(L_4=O(\ell_{\mathrm{sp}})\) and \(G_N=O(\ell_{\mathrm{sp}}^2)\).
This is conditional scaling, not a numerical prediction.

## Born--Infeld completion

Under the separate coherence-extensivity hypothesis, the tensorial completion of a
supplied Einstein infrared term remains of determinantal Born--Infeld form:

\[
\sqrt{-\det(g_{\mu\nu}+\ell_{\mathrm{sp}}^2R_{\mu\nu})}-\sqrt{-g}.
\]

This rigidity statement does not determine the finite Einstein coefficient.

## Interpretive status

Spectral geometry fixes the available local tensor structures and their cutoff
sensitivities.
It does not yet derive the positive finite gravitational coupling.
The remaining problem is to construct an independent matching principle from the
complete projected operator content.

## Links

- [Programme website](https://cosmochrony.org/science/spectral-gravity/gravity/)
- [Zenodo concept DOI](https://doi.org/10.5281/zenodo.18818721)

## Citation

> J. Beau, *Conditions for an Infrared Einstein Sector from Spectral Geometry*,
> Zenodo, 2026.

## Acknowledgements

Portions of the development benefited from iterative interactions with large language
models used as analytical assistants.
All claims, interpretations, and final formulations remain the author's responsibility.
