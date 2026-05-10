---
title: Graduate Internship at ORNL
description: "GNN surrogates for fiber composites and polycrystals at Oak Ridge National Laboratory — multitask elastoplastic modeling, fatigue prediction, and HydraGNN workflows."
---

# Graduate Internship at ORNL

May 2024 - Dec 2024; May 2025 - present, Oak Ridge, TN

---

**Summary**: At ORNL, I worked on reducing the computational cost of microstructure-sensitive materials modeling by building graph neural network surrogates for composites and polycrystals. My work focused on making structure-to-property prediction more scalable, more robust to heterogeneous microstructures, and more useful for downstream fatigue and damage studies.

**Mentor**: Massimiliano Lupo Pasini, Computational Coupled Physics, Computational Sciences and Engineering Division (CSED), Computing and Computational Sciences Directorate (CCSD), Oak Ridge National Laboratory

**Key outcomes**:

- Published paper on graph neural networks for 2D fiber-composite property prediction.
- Built multitask graph surrogates for ferrite-martensite polycrystals to accelerate elastoplastic and fatigue-relevant studies.
- Improved accuracy and efficiency relative to CNN baselines, including stiffness prediction with 160x fewer parameters and peak-strength prediction with better accuracy using 12x fewer parameters.
- Contributed to HydraGNN code quality and scientific machine learning workflows on Linux/HPC systems.

---

## Project Highlights

### 1. Fiber-composite surrogate modeling

**Situation**: High-fidelity homogenization of 2D fiber composites is expensive, especially when microstructures are statistically diverse, anisotropic at the SVE scale, and far from the RVE limit.

**Task**: Build a surrogate that can predict stiffness and strength directly from microstructure while remaining accurate for high material-contrast cases and practical for large parametric studies.

**Action**: I developed topology-based GNN workflows for 2D fiber composites, trained them to predict the full stiffness tensor together with peak-strength and brittle-fracture-related quantities, introduced physics-based normalization for extreme contrast ratios, and used Voronoi-derived features to improve learning in small-data regimes.

**Result**: The models remained robust across diverse microstructure configurations, achieved stiffness prediction with 160x fewer parameters than CNN baselines, improved peak-strength accuracy while using 12x fewer parameters, and led to a published paper in *Materials & Design*.

<p align="center">
<img src="/images/gro-jmade-graphical-abstract.png?raw=true" alt="Graphical abstract: GNN workflow for 2D fiber composite stiffness and strength prediction, Materials and Design 2025"/>
</p>

<p align="center">
<em>Graphical abstract (Caliskan et al., 2025, M&amp;D).</em>
</p>

### 2. Multitask polycrystal surrogate modeling

**Situation**: Elastoplastic response prediction for polycrystals typically requires large CPFEM ensembles, which becomes a bottleneck when studying variability, extreme responses, and fatigue-relevant random fields over many statistically distinct SVEs.

**Task**: Create a surrogate that preserves microstructure-sensitive variability while predicting both scalar elastoplastic measures and full stress-strain behavior across compositions and SVE sizes.

**Action**: I represented dual-phase ferrite-martensite polycrystals as grain-adjacency graphs with phase, geometry, orientation, and misorientation information, then developed multitask GNN surrogates that jointly predict elastic-plastic quantities of interest and stress-strain responses across martensite volume fractions and SVE sizes.

**Result**: The workflow supported population-level comparisons of finite-SVE variability and enabled statistically consistent random-field construction for mesoscale fatigue and damage analyses, making large ensemble studies more tractable.

## Selected Outputs


- **Caliskan, Erdem**, Reza Abedi, and Massimiliano Lupo Pasini. "Graph Neural Networks for Mechanical Property Prediction of 2D Fiber Composites." Materials & Design (2025): 114500. [Publication link](https://doi.org/10.1016/j.matdes.2025.114500)
- **Caliskan, Erdem**, Anik Das Anto, Massimiliano Lupo Pasini, Stephanie TerMaath, and Reza Abedi. "Multitask Graph Neural Networks for Elastoplastic Response Prediction in Dual-Phase Polycrystals." Journal of Materials Science: Materials Theory (under review). [Publication link](https://erdemcaliskan.github.io/papers/2026_Multitask_gnns_for_elastoplastic_response.pdf)
- **Caliskan, Erdem**, Anik Das Anto, Reza Abedi, and Massimiliano Lupo Pasini. "Probabilistic Multi-Task Graph Neural Network Surrogates for Elastic-Plastic Behavior and Fatigue Indicator Prediction in Polycrystalline Alloys." In SES Conference 2025, Atlanta, Georgia, USA, October 12-15, 2025.

**Methods/Stack**: HydraGNN, PyTorch, PyTorch Geometric, microstructure-derived graphs, grain-adjacency graphs, physics-based normalization, Voronoi-derived features, and Linux/HPC workflows.

---