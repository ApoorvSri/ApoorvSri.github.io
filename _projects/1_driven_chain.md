---
layout: page
title: Ergodicity breaking in a driven constrained chain
description: What happens when a system that cannot thermalize on its own is coupled to an environment
importance: 1
category: research
---

Most quantum many-body systems left to themselves come to equilibrium: local information about
how the system started gets scrambled into the whole, and after long enough you cannot recover it.
Kinetically constrained systems are an interesting exception. If the dynamics conserves not just
the total charge but also its dipole moment, then a particle cannot hop on its own — it can only
move if another particle moves the opposite way to compensate. That restriction alone, with no
disorder and no fine tuning, shatters the Hilbert space into a large number of disconnected
sectors, and the system never explores most of the states available to it.

The question my work with [Shovan Dutta](https://www.rri.res.in/people/faculty/shovan-dutta)
addressed is what survives when such a system is opened up. Real systems are never isolated, and
the usual expectation is that coupling to an environment washes out this kind of structure. We
drove a dipole-conserving spin chain with an incoherent pump at one end and loss at the other,
and asked what the system settles into.

It settles into a hierarchy. Rather than one unique steady state, the driven chain supports a
whole family of degenerate stationary states, and their structure can be read off from the way
probability flows between symmetry sectors labelled by the total charge and dipole moment. That
flow splits into blocks, starts from sources, and terminates in states that the drive can no
longer act on. Depending on the relative strength of pump and loss and on how local the
constraints are, the endpoints of that flow can be mixed steady states, noiseless subsystems, or
decoherence-free subspaces — all of them structures that retain a large amount of information
about how the chain was prepared. We also found that a dipole-conserving bulk suppresses the
steady-state current, so the chain resists carrying the charge that the drive is trying to push
through it.

What I like about the result is that it does not depend on the details. The argument runs on the
structure of the flow in Hilbert space, so it holds for any Hamiltonian and drive mechanism with
the same conservation laws. That also makes it something a cold-atom or superconducting-qubit
simulator could plausibly look for.

Published as
[SciPost Phys. **18**, 111 (2025)](https://scipost.org/SciPostPhys.18.3.111);
preprint at [arXiv:2411.03309](https://arxiv.org/abs/2411.03309).
