---
title: Syllabus
nav_order: 2
---

# Syllabus
{: .no_toc }

The course is built around three themes. The instructor lectures establish the
foundations of each theme; the reading group then explores recent work building
on those foundations.

> **Note:** paper links (arXiv / DOI) are being verified and will be added in a
> follow-up pass. A few citations below are flagged for verification.

1. TOC
{:toc}

---

## Part I — Foundations (instructor lectures)

### Theme 1 — Distances between distributions

**Motivation.** Training objectives (WGANs); regularizers for domain adaptation;
metric learning over entities that are themselves clouds of points (one sample =
many cells); downstream evaluation of generation quality (FID).

**Lecture content.**
- Integral probability metrics: distance = sup over a test-function class of the
  gap in expectations
- Maximum Mean Discrepancy (MMD)
- Wasserstein-1 distance
- A simple algorithm and setup for the W1 distance, with a 1D example (quantiles)

*Spine:* Gretton et al. 2012 (*A Kernel Two-Sample Test*) → Li et al. 2015
(*Generative Moment Matching Networks*).

### Theme 2 — Coupling particles across distributions

**Motivation.** Counterfactuals & causal inference (treated → control; the map
*is* the counterfactual); matching particles across contexts (cells across
timepoints); translation across incomparable spaces (one embedding space →
another).

**Lecture content.**
- Monge vs. Kantorovich formulations
- Entropic regularization & Sinkhorn (Cuturi 2013)
- Brenier's theorem (the OT map as the gradient of a convex potential)

*Spine:* Cuturi 2013 (*Sinkhorn Distances*) → Feydy et al. 2019
(*Interpolating between OT and MMD using Sinkhorn Divergences*).

### Theme 3 — Interpolating between distributions

**Motivation.** The flow/trajectory between two distributions is itself the
object of interest (e.g. music/sound effects); single-cell developmental
trajectories (unobserved states between timepoints); image/latent morphing;
transition paths in chemistry and physics.

**Lecture content.**
- Dynamic OT / Benamou–Brenier: the least-energy flow; geodesics = displacement
  interpolation
- Wasserstein barycenters
- Continuous normalizing flows → flow matching (Chen et al. 2018 → Lipman et al. 2023)

*Spine:* Chen et al. 2018 (*Neural ODEs*) → Lipman et al. 2023
(*Flow Matching for Generative Modeling*).

---

## Part II — Reading group

### Theme A — Distances

**A1. OT for domain adaptation**
- Optimal Transport for Domain Adaptation (Courty et al. 2017)
- DeepJDOT: Deep Joint Distribution Optimal Transport for Unsupervised Domain Adaptation (Damodaran et al. 2018)

**A2. Distributions as objects: metric learning over point clouds**
- Wasserstein Wormhole: Scalable Optimal Transport Distance with Transformers (Haviv et al. 2024)
- Generative Distribution Embeddings: Lifting Autoencoders to the Space of Distributions (2025) — *citation to verify*

### Theme B — Coupling

**B1. Supervised learning of Monge maps**
- Monge Gap (Uscidda & Cuturi 2023)
- Conditional Monge Gap (Driessen et al. 2026)
- *Related work (not presented):* CondOT (Bunne et al. 2022)

**B2. Relaxing balance: unbalanced OT**
- Scaling Algorithms for Unbalanced Optimal Transport (Chizat et al. 2018)
- Unbalancedness in Neural Monge Maps (Eyring et al. 2024)

**B3. Transport across incomparable spaces: Gromov–Wasserstein**
- Gromov–Wasserstein Averaging of Kernel and Distance Matrices (Peyré, Cuturi & Solomon 2016)
- Gromov–Wasserstein Alignment of Word Embedding Spaces (Alvarez-Melis & Jaakkola 2018)

### Theme C — Interpolating

**C1. OT couplings inside flow matching**
- OT-CFM: Conditional Flow Matching with minibatch OT (Tong et al. 2023)
- MMFM: Modeling complex system dynamics with flow matching across time and conditions (Rohbeck et al. 2025)

### Complementary readings on flow matching

**D1. Flow matching on structured domains**
- Riemannian Flow Matching on General Geometries (Chen & Lipman 2023)
- Discrete Flow Matching (Gat et al. 2024) — *year to verify*

**D2. Few-step & one-step flow matching**
- Flow Map Matching (Boffi et al. 2025)
- Mean Flow (Geng et al. 2025)

**D3. Guidance for conditional generation**
- Guided Flows for Generative Modeling and Decision Making (Zheng et al. 2023)
- CFG-Zero\*: Improved Classifier-Free Guidance (Fan et al. 2025)

### Applications

**E1. Single-cell genomics**
- Optimal-Transport Analysis of Single-Cell Gene Expression / Waddington-OT (Schiebinger et al. 2019)
- GENOT: Generative Entropic Neural Optimal Transport (Klein et al. 2024)

**E2. Music generation**
- *TBD — papers to be selected.*
