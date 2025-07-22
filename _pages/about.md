---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - "/wordpress/"
  - "/wordpress/index.html"
---

{% include base_path %}
I am a Computational Scientist and Ph.D. Candidate in Computing (CMSE) at [Boise State University](https://www.boisestate.edu/), affiliated with the School of Computing. My research centers on the development and implementation of numerical methods for continuum solvation models, with applications in catalysis and materials modeling. I specialize in high-performance computing (HPC), scientific code development, and the optimization of algorithms for large-scale simulations and data analysis.

### My Research

My research centers on developing high-accuracy numerical solvers for partial differential equations (PDEs) with **interface discontinuities** and complex geometries, particularly in **electrostatics**, **materials modeling**, and **multi-domain physics**. I work extensively with **immersed interface methods (IIM)** and **embedded boundary techniques**, crafting robust algorithms that preserve sharp jump conditions across irregular domains in both 2D and 3D.

At the core of my work is the integration of **spectral solvers** (e.g., discrete sine transforms) with **iterative Krylov methods** like GMRES to efficiently solve large-scale elliptic systems. I implement these solvers in hybrid **Python–Fortran** codebases optimized for **high-performance computing (HPC)** clusters. My goal is to create scalable, accurate numerical frameworks that bridge mathematical rigor with real-world applications in electrostatics, fluid interfaces, and materials science.

I also explore **data-driven acceleration** techniques—such as reduced models and RBF interpolation—to enable faster simulations without sacrificing physical accuracy. My work emphasizes **modularity**, **reproducibility**, and **performance portability**, ensuring that scientific computing pipelines remain adaptable across domains.

### Research Interests

* **Immersed Interface & Embedded Boundary Methods**
  I design finite difference and interpolation-based solvers for elliptic PDEs with interface jumps in complex domains, enabling accurate treatment of heterogeneous media and sharp interfaces.

* **Spectral & Krylov Solvers for Poisson-Type Equations**
  I combine fast sine/cosine transforms with iterative solvers (e.g., GMRES) to handle interface-coupled electrostatic systems with high accuracy and efficiency.

* **High-Performance Scientific Computing**
  My code runs on SLURM-based HPC clusters using MPI-parallel workflows and hybrid Python–Fortran backends, supporting large-scale 3D simulations with jump conditions and region-based source terms.

* **Radial Basis Function (RBF) Interpolation & Interface Fitting**
  I apply RBFs for accurate geometric representation of curved interfaces and for computing geometrical quantities (normals, curvatures) needed in jump condition enforcement.

* **In Silico Materials Modeling**
  I use DFT codes (Quantum ESPRESSO, ASE) to compute electrostatic and vibrational properties, connecting numerical interface solvers to electronic structure data.

* **Data-Driven Physics**
  While not my primary focus, I explore how machine learning and symbolic regression can be used to accelerate components of traditional PDE solvers or extract interpretable physical laws from simulation data.

### Technical Skills

* **Programming & Scientific Computing**
  Python (NumPy, SciPy, Matplotlib, SymPy), Fortran90/95, Bash, Git, SLURM job scripting

* **Numerical Solvers**
  Finite difference methods, discrete transforms (DST, DCT), iterative solvers (GMRES, BiCG), matrix-free methods, RBF interpolation, SVD/PCA analysis

* **Scientific Libraries & Tools**
  MPI, ASE, Phonopy, Quantum ESPRESSO, Matplotlib

* **HPC & Performance Optimization**
  MPI, hybrid Python–Fortran pipelines, job arrays, profiling with `gprof` and `line_profiler`, cluster deployment (HPC SLURM environment)

* **Visualization & Data Analysis**
  Matplotlib, ParaView, Plotly, Pandas, 3D visualization ( matplotlib 3D), LaTeX 


Education
======

- **Ph.D. in Computing (Computational Mathematics Science and Engineering)**  
  [Boise State University](https://www.boisestate.edu/), Boise, ID, USA — Expected to graduate by Fall 2026  

- **M.Sc. in Mathematical Sciences (Climate modeling and Data Assimilation)**  
  [African Institute for Mathematical Sciences (AIMS)](https://aims.ac.rw/), Kigali, Rwanda — 2020–2021  

- **B.ScED. Mathematics & Physics**  
  [Makerere University](https://mak.ac.ug/), Kampala, Uganda— 2014–2018  

Recent Updates
======

- **April 2025**  
  Awarded the **[ CASCADE RAIN 2025 travel award ](https://sites.google.com/oregonstate.edu/rain2025/travel-support)** Awarded the Cascade RAIN 2025 Travel Award in recognition of graduate research contributions in applied mathematics. The award supports conference travel and highlights emerging researcgh in the field.

- **September 2024**  
  Received a **ACSFALL2024 best oral presentation Award** **[ACSFALL2024](https://acs.digitellinc.com/p/s/accelerating-catalytic-advancements-through-the-precision-of-high-throughput-experiments-and-calculations-609622)** at the “Accelerating Catalytic Advancements Through the Precision of High-Throughput Experiments & Calculations” symposium during the ACS Fall 2024 Conference in Denver, CO. The award recognized excellence in presenting cutting-edge research in computational catalysis.

- **July 2024**  
  Attended a workshop on Quantum multiscale modeling at BSU organized by Dr. Oliviero Andreussi as his collaborators  **[Quantum multiscale modeling](http://www.quantum-multiscale.org/)** 

Awards
======

- **2024**  
  - ACSFALL2024 best oral presentation   
  - CASCADE RAIN Travel Awards  – For presentations at major applied mathematics and Numerical methods
- **2021**  
  - [Boise State GEM Scholarship](https://www.boisestate.edu/graduatecollege/funding/merit-based-gem-scholarship/) – Merit-based graduate award  
  - Graduate Assistantship – Research funding from Boise State University  
  - AIMS Master's Scholarship (Mastercard Foundation) – Full scholarship for climate-focused graduate studies

- **2015**  
  - The Uganda Government National Merit Scholarship – Full undergraduate scholarship based on academic excellence at Makerere University
