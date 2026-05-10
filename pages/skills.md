---
title: Skills
description: "Where I use simulation, coding, ML, HPC, and open-source tools across research, coursework, and engineering projects."
---

# Skills

This page summarizes the simulation, coding, machine learning, HPC, and open-source tools I use most often, with examples from research, coursework, and engineering projects.

## Simulation/CAE

- `LS-DYNA`: used in my [Graduate Research Assistant at UTK](/pages/experience/GRA) work on an ARL-funded project for high-speed impact simulations of resonant ceramic metamaterials, including Johnson-Holmquist 2 material modeling through UMAT and transient response studies. I also used ALE simulations for fluid-microstructure interaction problems. These workflows involved thousands of simulations on HPC systems, with Python, COMSOL, and LS-PrePost used for preprocessing and postprocessing.
- `Abaqus`: used in my [UTK research](/pages/experience/GRA) on an AFOSR-funded project for user-element-based phase-field modeling, including residual eigenstrain effects. I used Python scripts and Abaqus/CAE for preprocessing and postprocessing.
- `Ansys (Workbench, Composite PrepPost (ACP), Static Structural, Thermal, SpaceClaim)`: used across multiple engineering projects, including turbopump structural, thermal, and fatigue analyses at [ITUNOVA](/pages/experience/itunova), composite structural analysis at [Baykar](/pages/experience/baykar), composites and metallic structural analysis at [ITU Facilis](/pages/experience/facilis), and graduate coursework in my [MSc studies](/pages/education/msc).
- `COMSOL`: used for preprocessing and mesh generation for LS-DYNA simulations in my [UTK research](/pages/experience/GRA).
- `SolidWorks`: used for CAD preparation and engineering design workflows, especially in turbopump work at [ITUNOVA](/pages/experience/itunova) and vehicle development at [ITU Facilis](/pages/experience/facilis). [View my Certified SolidWorks Associate (CSWA) certification](https://cv.virtualtester.com/qr/?b=SLDWRKS&i=C-M3KZAEUXNN).
- `Siemens NX`: used in broader CAD/CAE workflows for geometry cleanup, model organization, and engineering design iteration in [ITU Facilis](/pages/experience/facilis) composite vehicle development.
- `nCode`: used in [MSc fracture mechanics coursework](/pages/education/msc) for fatigue and crack-growth analysis.
- `NASGRO`: used in [MSc fracture mechanics coursework](/pages/education/msc) for crack propagation and fracture mechanics analysis.

## User subroutines

- `LS-DYNA UMAT`: used in my [UTK research](/pages/experience/GRA) to develop and support nonlinear material models for ceramics.
- `Abaqus UEL (FORTRAN)`: used in my [UTK research](/pages/experience/GRA) to extend phase-field formulations to include thermal and residual eigenstrain effects.
- `MATLAB`: used for subroutine prototyping, reduced-order model development, postprocessing, and coursework, including finite element and dynamics assignments in my [MSc](/pages/education/msc), finite-volume work in [PhD coursework](/pages/education/phd), and scripting support at [ITUNOVA](/pages/experience/itunova).

## Scientific computing / in-house code

- `DG solvers in C++`: used in my [UTK research](/pages/experience/GRA) and [PhD coursework](/pages/education/phd) to study discontinuous Galerkin formulations and compare numerical implementations. [GitHub repository](https://github.com/erdemcaliskan/DGFEM1D).
- `FEM solvers in C++ and Python`: used for research and coursework on nonlinear finite elements, including constitutive model implementation in [`deal.II`](/pages/education/phd) and related custom numerical studies.
- `FV solvers in C++ and Python`: used for numerical method development and verification for a hyperbolic heat equation solver in [PhD coursework](/pages/education/phd).
- `Phase-field implementations`: used in my [UTK research](/pages/experience/GRA) for fracture and microstructure-sensitive computational mechanics studies.

## ML/AI

- [`HydraGNN`](https://github.com/ORNL/HydraGNN): used during my [Graduate Internship at ORNL](/pages/experience/GRO) for graph-based surrogate modeling workflows and code-quality contributions. [GitHub repository](https://github.com/ORNL/HydraGNN).
- `PyTorch`: used in my [ORNL work](/pages/experience/GRO) to build graph neural network surrogates for fiber composites and ferrite-martensite polycrystals within the HydraGNN framework.
- `PyTorch Geometric`: used in the same [ORNL projects](/pages/experience/GRO) to represent microstructures as graphs and train multitask surrogate models. I am familiar with data objects, transformations, and message-passing workflows in PyTorch Geometric.
- `Probabilistic modeling / uncertainty quantification`: used in my [ORNL work](/pages/experience/GRO) for uncertainty-aware fatigue prediction and microstructure-to-property learning.

## HPC

- `Linux`: my main environment for [UTK research](/pages/experience/GRA), [ORNL internship](/pages/experience/GRO), and [MSc thesis work](/pages/education/msc), including simulation, machine learning, and scientific software workflows.
- `Slurm`: used to submit, monitor, and manage large simulation and training jobs on shared HPC clusters.
- `MPI`: used when building and running scalable scientific software on cluster systems for larger numerical studies.
- `OpenMP`: used in shared-memory performance settings for compiled scientific codes and related HPC workflows.
- `CMake`: used when compiling and maintaining research software stacks, especially in the HPC and open-source workflows described in my [UTK research](/pages/experience/GRA).

## Open source

- `deal.II`: used in [PhD coursework](/pages/education/phd) for nonlinear finite element implementations, including linear elasticity, Neo-Hookean response, and J2 plasticity.
- `OpenFOAM`: used in [ITU Facilis](/pages/experience/facilis) and [Gas Dynamics coursework](/pdf/Gas_Dynamics_TP.pdf) for CFD analysis of the vehicle body to improve drag and lift, and to study shock waves.
- `LAMMPS`: used in my [MSc thesis](/pages/education/msc) for reactive molecular dynamics simulations of boron nanotubes on HPC systems.
- `NumPy`: used throughout data preparation, postprocessing, and research scripting in simulation and machine learning workflows.
- `pandas`: used for organizing tabular outputs and derived feature and response data in research workflows.
- `scikit-learn`: used for baseline machine learning utilities, data preprocessing, and comparative analysis in scientific ML workflows.

## Related pages

- [Graduate Internship at ORNL](/pages/experience/GRO)
- [Graduate Research Assistant at UTK](/pages/experience/GRA)
- [Mechanical Engineer, ITUNOVA Technologies](/pages/experience/itunova)
- [Intern, Baykar Technologies](/pages/experience/baykar)
- [Intern, Turkish Aerospace Industries - ITU Very Light Aircraft Project](/pages/experience/tai)
- [Team Member, ITU Facilis Vehicle Team](/pages/experience/facilis)
- [PhD at UTK](/pages/education/phd)
- [MSc at ITU](/pages/education/msc)