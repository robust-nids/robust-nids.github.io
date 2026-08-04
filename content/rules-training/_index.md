---
title: "Rules & Training"
description: "Encode security domain knowledge as formal rules and use them to train classifiers that provably behave correctly."
date: 2026-03-25
---

## Beyond Fitting the Data

Standard ML training optimizes a loss function against labeled examples. But a classifier that fits the data perfectly can still behave absurdly — flagging benign traffic as an attack because of an irrelevant feature, or missing an obvious attack variant it hasn't seen before. Domain experts *know* things about what a correct classifier should do, but that knowledge gets lost when training is purely data-driven.

## What You'll Work On

In this theme, you'll formalize security properties as logical rules and integrate them into the neural network training process using the [Vehicle specification language](https://vehicle-lang.github.io/tutorial/).

Possible thesis directions:

- **Property elicitation:** Work with security researchers to identify and formalize properties that a correct NIDS must satisfy (e.g., "a flow with no payload bytes should never be classified as a data exfiltration attack")
- **Training with constraints:** Implement differentiable logic loss terms that penalize property violations during training
- **Counterexample-guided refinement:** Use formal verification tools to find inputs where the classifier violates a property, then retrain to fix those violations
- **Comparative evaluation:** Measure how property-guided training affects accuracy, robustness, and generalization compared to standard training

## What You'll Learn

- Formal specification of security properties
- Neuro-symbolic AI techniques (combining logic with neural networks)
- The Vehicle specification language and verification toolchain
- Adversarial robustness evaluation

## Project Results

{{< results theme="rules-training" >}}

## Relevant Literature

- [Formally Verifying Robustness and Generalisation of Network Intrusion Detection Models. Flood et al., ACM 2024](https://dl.acm.org/doi/10.1145/3672608.3707927)
- [Bad design smells in benchmark NIDS datasets. Flood et al., EuroS&P 2024](https://lirias.kuleuven.be/retrieve/770268)
- [Induction and Recursion Principles in a Higher-Order Quantitative Logic. Bacci & Mogelberg, 2025](https://arxiv.org/abs/2501.18275)
- [The Vehicle language tutorial](https://vehicle-lang.github.io/tutorial/)

**Supervisors:** Alessandro Bruni (ITU), Giorgio Bacci (AAU) -- see [Team](/team/)
