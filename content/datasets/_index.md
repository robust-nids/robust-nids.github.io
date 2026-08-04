---
title: "Datasets"
description: "Build realistic datasets that expose the gap between lab-trained classifiers and real-world network security."
date: 2026-03-25
---

## The Problem with Today's NIDS Datasets

Most network intrusion detection research relies on datasets collected in controlled lab environments or generated synthetically. These datasets contain "design smells" — accidental patterns that classifiers exploit to achieve high accuracy in the lab but that don't hold up in deployment. A classifier might learn to flag attacks based on packet timing artifacts from the lab network rather than the actual malicious payload.

## What You'll Work On

In this theme, you'll help build datasets that bridge the gap between lab and reality, working with **TDC NET** to validate against real network conditions.

Possible thesis directions:

- **Dataset auditing:** Analyze existing benchmark datasets (CIC-IDS, UNSW-NB15, etc.) for design smells and data leakage using the methodology from Flood et al.
- **Realistic data collection:** Design and run experiments to capture network traffic under controlled attack scenarios
- **Feature engineering:** Investigate which network flow features are robust across environments and which are artifacts of the collection setup
- **Public release:** Prepare and document a curated dataset for the research community

## What You'll Learn

- Network traffic analysis and feature extraction
- Experimental methodology for security research
- Working with industry-grade network infrastructure
- Critical evaluation of ML benchmarks

## Project Results

{{< results theme="datasets" >}}

## Relevant Literature

- [Bad design smells in benchmark NIDS datasets. Flood et al., EuroS&P 2024](https://lirias.kuleuven.be/retrieve/770268)
- [Evaluating model robustness to adversarial samples in network intrusion detection. Schneider et al., IEEE Big Data 2021](https://ieeexplore.ieee.org/document/9671580)
- [Formally Verifying Robustness and Generalisation of Network Intrusion Detection Models. Flood et al., ACM 2024](https://dl.acm.org/doi/10.1145/3672608.3707927)

**Supervisors:** Alessandro Bruni (ITU), Nicola Dragoni (DTU) -- see [Team](/team/)
