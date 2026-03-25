---
title: "Privacy-Preserving Training"
description: "Enable multiple organizations to jointly train intrusion detectors without sharing sensitive network data."
date: 2026-03-25
---

## The Data Sharing Problem

Banks, hospitals, and telecom providers all face network attacks — but they can't pool their data to train better detectors. Privacy regulations, competitive concerns, and security policies prevent it. Yet a model trained on one organization's data may not generalize to another's network. How do you train a robust classifier across organizations without anyone revealing their data?

## What You'll Work On

This theme explores the intersection of **secure multiparty computation (MPC)**, **federated learning**, and **differentiable logics**. The goal is to enable collaborative training where logical constraints improve robustness, and cryptographic protocols protect privacy.

Possible thesis directions:

- **Feasibility study:** Implement a basic federated NIDS training pipeline with MPC (using frameworks like [MP-SPDZ](https://eprint.iacr.org/2020/521)) and measure the computational overhead
- **DL under MPC:** Investigate which differentiable logics are tractable under secure computation — some loss functions are much more expensive to compute securely than others
- **Protocol design:** Design new training protocols that balance privacy guarantees, model accuracy, and computational cost
- **Multi-valued logics for MPC:** Explore whether new logics can be designed specifically for efficiency under secure computation

## What You'll Learn

- Secure multiparty computation (garbled circuits, secret sharing)
- Federated learning architectures
- Differentiable logics and neuro-symbolic AI
- Privacy-preserving machine learning

## Relevant Literature

- [DL2: Training and Querying Neural Networks with Logic. Fischer et al., PMLR 2019](https://proceedings.mlr.press/v97/fischer19a.html)
- [MP-SPDZ: A Versatile Framework for Multi-Party Computation. Keller, CCS 2020](https://eprint.iacr.org/2020/521)
- [Practical Secure Aggregation for Federated Learning on User-Held Data. Bonawitz et al., NeurIPS 2016](https://proceedings.neurips.cc/paper/2016/hash/2bfa9f3c0ec4b1a90a5b7c6b0b8ef4d4-Abstract.html)
- [Logic of Differentiable Logics: Towards a Uniform Semantics of DL. Slusarz et al., LPAR 2023](https://easychair.org/publications/paper/8v7d)
- [Formally Verifying Robustness and Generalisation of NIDS. Flood et al., ACM 2024](https://dl.acm.org/doi/10.1145/3672608.3707927)

**Supervisors:** Alessandro Bruni (ITU), Nicola Dragoni (DTU) -- see [Team](/team/)
