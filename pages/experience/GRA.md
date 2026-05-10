---
title: Graduate Research Assistant at UTK
description: "Computational mechanics research at UTK — resonant metamaterials under impact, high-strain-rate fracture, UMAT/UEL development, and HPC simulation workflows."
---

# Graduate Research Assistant at UTK

January 2022 - present, Knoxville, TN

---

**Summary**: At UTK, I worked on computational mechanics for impact- and blast-relevant microstructured materials, with emphasis on resonant metamaterials, high-rate response, and simulation workflows that make large design studies feasible. My work focused on PDE solvers (FEM, DG, phase-field), constitutive modeling, and research-computing infrastructure.

**Advisor**: Prof. Reza Abedi

**Project context**: ARL-funded project *Innovative Material Systems for Engaging Ballistic Energy*, with Alireza V. Amirkhizi and Reza Abedi.

**Key outcomes**:

- Published paper on time-domain analysis of locally resonant elastic metamaterials under impact.
- Demonstrated ceramic metamaterial designs that slow wave propagation by 5x relative to conventional materials.
- Showed that graded metamaterials can reduce energy transfer by 6x versus uniform metamaterials, while material damping can amplify performance up to 4x versus monolithic slabs.
- Developed UMAT and postprocessing workflows for ceramic (Johnson-Holmquist 2) and clay material models, alongside broader simulation support for the group's research workflows.

---

## Contributions

### 1. Time-domain analysis of resonant metamaterials

**Situation**: Many metamaterials studies emphasize frequency-domain analysis of infinite periodic systems, which does not fully capture finite-size effects or realistic impact and blast scenarios.

**Task**: Develop a simulation framework for lightweight single-material locally resonant ceramic metamaterials and evaluate whether they can outperform conventional protective slabs under transient loading.

**Action**: I used time-domain finite element analysis to study finite metamaterial slabs under impact-relevant loading, compared uniform and graded designs, and examined the roles of resonance, damping, boundary conditions, and loading scenarios in energy mitigation.

**Result**: The metamaterial designs slowed wave propagation by 5x versus conventional materials, graded slabs reduced energy transfer by 6x relative to uniform metamaterials, material damping amplified performance up to 4x versus monolithic slabs, and the work led to a published paper in *Mechanics of Advanced Materials and Structures*.

<p align="center">
<img src="/images/gra-mams-graphical-abstract.png?raw=true" alt="Graphical abstract: Time domain analysis of locally resonant elastic metamaterials under impact, Mechanics of Advanced Materials and Structures 2026"/>
</p>

<p align="center">
<em>Graphical abstract (Caliskan et al., 2026, MAMS).</em>
</p>

### 2. Nonlinear material modeling and simulations

- High-speed impact and blast simulations for ceramic materials and resonant microstructured media.
- UMAT development in LS-DYNA for ceramic and clay material models, including Johnson-Holmquist 2 based work for ceramics.
- Postprocessing and supporting workflows for nonlinear simulation studies.

<div style="display: flex; justify-content: center; gap: 24px; align-items: flex-start;">
  <img src="/images/hex-jh2.gif?raw=true" alt="LS-DYNA simulation of hexagonal ceramic metamaterial under high-speed impact with Johnson-Holmquist 2 material model" style="max-width: 220px; width: 100%; height: auto; border-radius: 8px;" />
  <img src="/images/square-jh2.gif?raw=true" alt="LS-DYNA simulation of square ceramic metamaterial array under impact with Johnson-Holmquist 2 constitutive model" style="max-width: 220px; width: 100%; height: auto; border-radius: 8px;" />
</div>
<p align="center">
  <em>LS-DYNA simulations of hexagonal and square Alumina (Al<sub>2</sub>O<sub>3</sub>) metamaterials under impact<br>
  with Johnson-Holmquist 2 material model. </em>
</p>
<p align="center">
  <img src="/images/ceramic.gif?raw=true" alt="Simulation of boron carbide / silicon carbide ceramic composite" style="max-width: 220px; width: 100%; height: auto; border-radius: 8px;" />
</p>
<p align="center">
  <em>Boron carbide (B<sub>4</sub>C)/silicon carbide (SiC) ceramic composite simulation. See more in <a href="/pages/experience/GRA">GRA at UTK</a>.</em>
</p>


### 3. Computational methods and research infrastructure

- Incorporated residual eigenstrain into an Abaqus UEL phase-field subroutine to account for thermal effects.
- Delivered arbitrary Lagrangian-Eulerian (ALE) simulations to investigate fluid-microstructure interaction.
- Studied a 1D discontinuous Galerkin solver in C++ for formulation comparison.
- Trained my Ph.D. group members on HPC usage, workflows, and compiling. I maintained the research-computing environment in our lab through compiling, benchmarking, and troubleshooting support.

## Selected Outputs

- **Caliskan, Erdem**, Willoughby Cheney, Weidi Wang, Thomas Plaisted, Alireza V. Amirkhizi, and Reza Abedi. "Time domain analysis of locally resonant elastic metamaterials under impact." Mechanics of Advanced Materials and Structures 33, no. 1 (2026): 2619034. [Publication link](https://doi.org/10.1080/15376494.2026.2619034)
- Abedi, Reza, Colin Furey, Farhad Pourkamali-Anaraki, Giang Huynh, **Erdem Caliskan**, and Alireza V. Amirkhizi. "Analyzing fragmentation response of heterogeneous ring using the method of characteristics and machine learning techniques." Computer Methods in Applied Mechanics and Engineering 436 (2025): 117709. [Publication link](https://doi.org/10.1016/j.cma.2024.117709)
- Cheney, Willoughby, Weidi Wang, Reza Abedi, **Erdem Caliskan**, and Alireza V. Amirkhizi. "Time Domain Parameter Extraction for High-Efficiency Reduced Order Models of Resonant Microstructured Media." Manuscript in preparation.

**Methods/Stack**: LS-DYNA UMAT, Abaqus UEL, time-domain finite element analysis, ALE simulations, C++, and Linux/HPC workflows.

---