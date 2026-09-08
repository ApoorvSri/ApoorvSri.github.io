---
layout: page
title: Ginzburg–Landau theory for high-T_c superconductors
description: A microscopic derivation within the extremely correlated Fermi liquid framework
importance: 3
category: research
---

The cuprate superconductors remain among the least understood phases of matter in
condensed matter physics. Their key feature — superconductivity emerging out of a doped
Mott insulator, with a phase diagram structured around a mysterious pseudogap phase and a
*d*-wave superconducting dome — places them squarely outside the reach of the conventional
BCS framework and the Gorkov derivation that underpins it. Phenomenological
Ginzburg–Landau (GL) theories exist, but they take the order parameter and its free energy
as given rather than deriving them from the microscopic Hamiltonian, and in so doing they
lose the connection between the GL coefficients and the strongly correlated electron physics
underneath.

My master's thesis, supervised by Prof. T. V. Ramakrishnan (JNCASR / IISc) and
co-advised by Prof. S. R. Hassan (IMSc) and Prof. N. S. Vidhyadhiraja (JNCASR),
attempted a fully microscopic derivation of a GL-like free energy functional for cuprate
superconductors, staying throughout in the Hubbard *X*-operator (projected-electron)
representation that enforces the no-double-occupancy constraint exactly.

**Strategy.** Starting from the extremely correlated Fermi liquid (ECFL) framework of
Shastry, a Schrieffer–Wolff transformation at order $1/U$ yields an effective low-energy
Hamiltonian in which the residual intersite pair attraction is controlled by the exchange
coupling $J$. Decoupling the resulting four-fermion interaction via a Hubbard–Stratonovich
transformation introduces an auxiliary bosonic field whose amplitude is the spin-singlet
nearest-neighbour Cooper pair amplitude — the natural order parameter. A cumulant
expansion of the resulting partition function then yields the free energy functional order
by order in the order parameter, with GL coefficients $A$, $B$, $C$ expressed as
integrals over the single-particle retarded Green's functions of the correlated metal.
These Green's functions are supplied by the self-consistent ECFL theory of Hassan et al.,
which captures the strongly renormalised spectral weight characteristic of the underdoped
cuprates.

**What we found.** The derived coefficients reproduce the correct qualitative trends: the
sign change in $A$ tracks the superconducting dome $T_c(x)$, and the two-temperature-scale
structure — the pseudogap $T^*(x)$ above $T_c$ — is visible in the behaviour of the
coefficients across the phase diagram. Quantitatively, however, the onset temperatures are
significantly underestimated. The source of this discrepancy is identifiable: it traces to
the decoupling approximation, which replaces the four-point $X$-operator correlator by a
product of two local single-particle Green's functions — the leading term of a $1/Z$
expansion, valid in the overdoped Fermi-liquid regime but insufficient in the
strongly underdoped and pseudogap regions where non-local and dynamic vertex
corrections are of the same order as the bubble contribution.

**What comes next.** The natural resolution is to derive, within the same Hubbard
*X*-operator framework, a Bethe–Salpeter-like equation of motion for the two-particle
(bosonic pair) propagator rather than decoupling it into a product of single-particle ones.
This is a substantially more involved calculation — the non-trivial operator algebra of
Hubbard *X*-operators makes even the formulation of the equation of motion technically
demanding — but it is the one route that keeps the derivation both microscopic and honest
about the strongly correlated nature of the system. This direction is being actively pursued.

M.S. thesis, Indian Institute of Space Science and Technology, March 2025.
[Download thesis (PDF)]({{ '/assets/pdf/SC20B146MastersThesis Final (1).pdf' | relative_url }})
