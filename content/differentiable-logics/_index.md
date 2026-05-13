---
title: "Differentiable Logics"
description: "Advance the mathematical foundations that make it possible to train neural networks with logical constraints."
date: 2026-03-25
---

## The Theory Behind the Practice

Differentiable logics are the engine that powers this entire project. The idea: take a logical formula expressing a desired property (e.g., "the classifier is robust to small perturbations") and interpret it as a differentiable function over real numbers. This function can then serve as a loss term during neural network training — the optimizer simultaneously fits the data *and* satisfies the logical specification.

But the theory is still young. Current differentiable logics have limitations in expressivity, numerical stability, and the guarantees they provide. Extending them is both a mathematical and an engineering challenge.

## What You'll Work On

This theme is for students who enjoy the interplay between theory and implementation. You'll work on the foundations of differentiable logics and their realization in tools like [Vehicle](https://vehicle-lang.github.io/tutorial/).

Possible thesis directions:

- **New operators:** Extend existing differentiable logic frameworks with quantifiers, induction principles, or recursion (building on Bacci & Mogelberg's work on higher-order quantitative logic)
- **Formalization:** Contribute to the Coq/Rocq formalization of differentiable logics, ensuring mathematical correctness of the framework
- **Tool development:** Extend the Vehicle specification language to support new property types or improve its compilation to loss functions
- **Benchmarking:** Systematically compare different differentiable logics (Lukasiewicz, product, Goedel, DL2) on NIDS training tasks

## What You'll Learn

- Differentiable logics and quantitative semantics
- Proof assistants (Coq/Rocq) and formal verification
- The Vehicle specification language
- How theoretical advances translate into practical ML improvements

## Relevant Literature

- [Taming Differentiable Logics with Coq Formalisation. Affeldt et al., ITP 2024](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.ITP.2024.4)
- [A Foundation for Differentiable Logics using Dependent Type Theory. Affeldt, Bruni, Komendantskaya, Ślusarz, Stark, 2026](https://arxiv.org/abs/2602.23878)
- [Induction and Recursion Principles in a Higher-Order Quantitative Logic. Bacci & Mogelberg, 2025](https://arxiv.org/abs/2501.18275)
- [Propositional logics for the Lawvere quantale. Bacci et al.](https://entics.episciences.org/12292)
- [Polynomial Lawvere Logic. Bacci et al.](https://arxiv.org/abs/2402.03543)
- [The Vehicle language tutorial](https://vehicle-lang.github.io/tutorial/)

**Supervisors:** Giorgio Bacci (AAU), Alessandro Bruni (ITU) -- see [Team](/team/)
