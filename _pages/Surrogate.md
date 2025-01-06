---
layout: archive
title: ""
permalink: /Surrogate/
author_profile: true
---


## Inductor Magnetic Energy Estimation Based on a MLP Surrogate Model [(PDF)](https://o2-ch4.github.io/files/Surrogate_Inductor.pdf) 


- **Context**: This project, undertaken as part of a graduate course in machine learning, explored the use of machine learning (ML) and deep learning (DL) methods to create fast and accurate surrogate models for evaluating the magnetic energy of inductor designs.

- **Overview**: The objective was to approximate the computationally intensive mapping typically performed by Finite Element Analysis (FEA), a method widely used to solve Partial Differential Equations (PDEs) for design evaluation in engineering. For example, Computational Fluid Dynamics (CFD) simulations are often employed to assess the aerodynamic performance of aircraft designs by calculating metrics like lift and drag. Similarly, this project focused on replacing FEA computations with ML-based surrogate models to significantly reduce the time required for evaluating complex systems, potentially accelerating design cycles from weeks to seconds.

- **Details**: The study focused on inductor designs, with the target metric being their magnetic energy, which depends on multi-dimensional design features such as topology. To achieve this, various ML models, including multi-layer perceptrons (MLPs), were tested for their ability to accurately approximate the FEA mappings. The research relied on a proprietary dataset of 100,000 samples provided by a Swiss collaborator from iCoSys (Institute of Complex Systems, Fribourg, University of Applied Sciences of Western Switzerland).


---

