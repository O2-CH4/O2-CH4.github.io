---
layout: archive
title: "About"
permalink: /
author_profile: true
---

## Overview

I am a Canadian AI graduate interested in the science and engineering of intelligence and advanced autonomy. I recently completed my second M.Sc. in Computer Science at the [Mila AI Institute](https://mila.quebec/), where I studied state representation learning for deep reinforcement learning under the supervision of [Pablo Samuel Castro](https://scholar.google.com/citations?user=jn5r6TsAAAAJ&hl=en), leading to a survey published in *[Transactions on Machine Learning Research](https://arxiv.org/pdf/2506.17518)*. I also contributed to multi-agent reinforcement learning research at Mila, collaborating with [Juan Duque](https://juanduquevan.github.io/) under the supervision of [Aaron Courville](https://scholar.google.com/citations?user=km6CP8cAAAAJ&hl=en) and [Hugo Larochelle](https://scholar.google.com/citations?user=U89FHq4AAAAJ&hl=en) on opponent-shaping methods for improving cooperation in climate and economic simulation settings, leading to a recent [publication](https://openreview.net/pdf?id=ex93RVyP5r) co-presented at ICLR 2026.

Previously, I conducted deep learning research for brain-computer interfaces in the laboratory of [Christian Ethier](https://scholar.google.com/citations?user=9CzYcbAAAAAJ&hl=en) at the [CERVO Brain Research Center](https://cervo.ulaval.ca/en/), developing neural decoding pipelines from raw intracortical signals. More recently, I worked on applied AI R&D at Bombardier Aerospace and Bentley Systems, including deep learning for flight-test data analysis, synthetic sensor modeling, and reinforcement learning applications.

My long-term goal is to contribute to increasingly capable, robust, safe, and trustworthy autonomous systems operating in complex real-world environments, including spacecraft, aircraft, drones, maritime systems, ground vehicles, and robotics.

---

## Research Interests

**Focus:** I am interested in understanding and improving the core building blocks of intelligent autonomous systems: perception, representation learning, world modeling, planning, control, uncertainty, adaptation, and multi-agent coordination.

**Direction:** I am particularly interested in how autonomous systems can learn useful abstractions from high-dimensional sensory observations and action spaces, leverage memory and prior knowledge, generalize across multiple tasks, estimate uncertainty, and use predictive world models to plan and adapt efficiently in dynamic environments.

**Vision:** Ultimately, I hope to contribute to the scientific and engineering foundations required for increasingly capable, robust, and trustworthy autonomous systems. I believe that achieving this across domains such as space, aviation, robotics, maritime systems, and ground vehicles will require significant advances beyond current capabilities. Although today's autonomous systems perform remarkably well in increasingly structured settings, many still depend on human supervision when faced with unexpected situations, long-horizon reasoning, or complex multi-agent interactions. I am interested in developing the learning, reasoning, planning, and coordination mechanisms needed to enable more capable, reliable, and increasingly independent autonomous systems.

---

## Publications

### [A Survey of State Representation Learning for Deep Reinforcement Learning](#)

*Transactions on Machine Learning Research, 2025*  
**Ayoub E., Pablo Samuel Castro**  
Comprehensive survey of state representation learning methods, evaluation protocols, and open challenges in deep reinforcement learning.

### [Towards Climate Investment Policies Informed by Reinforcement Learning](#)

*International Conference on Learning Representations, 2026*  
**Juan Duque, Razvan C., Ayoub E., Aaron Courville, Hugo Larochelle**  
Study on opponent-shaping multi-agent reinforcement learning for cooperation in climate-economic social dilemmas.

---

## Selected Graduate Coursework

Information Theory; Combinatorial Optimization; Machine Learning; Reinforcement Learning; Representation Learning; Theoretical Principles of Deep Learning; Robot Learning; Towards AGI: Scaling, Emergence, Alignment; Design and Simulation of Industrial Intelligent Systems; 3D Perception for Autonomous Vehicles; Natural Language Processing; Bioinstrumentation and Biomedical Microsystems; Quantum Computing.

---

## Selected Projects

*Selected projects from graduate coursework, research, industry R&D, personal exploration, and MVP-style startup ideas.*

<div style="height: 0.6rem;"></div>

### ▸ *Study - Examining the Road Ahead to Fully Autonomous Systems Across Domains* *(Current)*

* **Goal:** Reviewing and formalizing the core building blocks of autonomy across domains, including humanoid robots, drones, road vehicles, aircraft, spacecraft, aircraft networks, spacecraft constellations, and maritime systems.
* **Components:** Studying the current state of autonomous systems, the main characteristics of fully autonomous systems, and the technical gaps that must be bridged to reach robust, reliable, and increasingly independent autonomy.
* **collaborations:** Feel free to message me for details or if interested to contribute or advise in any way!

<div style="height: 0.8rem;"></div>



### ▸ *Deep Learning for Virtual Sensing Development* *(Bombardier Aerospace, 2025)*

* **Overview:** Worked on deep virtual sensors for synthetic air-data sensing and flight-test data analysis in safety-critical aerospace systems, supervised by Dr. Emmanuel Germanine. The work used deep learning on real aircraft flight-test data, where signals are noisy, variable across flight phases, and limited by real aircraft operations.

* **Importance:** The motivation was to build stronger backup sensing for aircraft state estimation. In aviation, wrong or inconsistent air-data measurements can quickly affect pilot awareness, automation behavior, and control decisions, as seen in accidents such as Air France 447 and the Boeing 737 MAX accidents. This becomes even more important for future aircraft such as flying wings and blended-wing bodies, where safe flight may depend strongly on onboard estimation and control.

* **Technical details:** Built pipelines using real flight-test data rather than simulation, so the models had to learn from limited flight envelopes. The work included signal cleaning, flight-phase detection, feature selection, train/test splitting, preprocessing, postprocessing, evaluation by flight phase, feature analysis, and ablations over architectures, losses, hyperparameters, model size, dataset size, filtering choices, input signals, aircraft type, and flight-test conditions.

* **Key distinction:** Unlike many related approaches that rely on GPS, frontal/static pressure data, or full-envelope simulation, we avoided these assumptions to make the pipeline closer to a real degraded-sensing case. This made the task harder, but more relevant to aircraft that must detect bad information, use backup sensors, validate aircraft state, and keep operating safely when some signals are missing or unreliable.

* **Research direction:** I see this area as open for many improvements in learned backup sensing, sensor redundancy, anomaly detection, and aircraft-state validation. I would be glad to continue research or R&D in this direction, especially for future autonomous aircraft and other safety-critical systems. Open to collaboration and discussion.


<div style="height: 0.8rem;"></div>

### ▸ *Weight-Space Representation Learning and FDM Learning for Parameter-Space “Warping”* *(Mila, 2025)*

* **Overview:** Explored whether learned representations of neural network weights, combined with forward dynamics models (FDMs) trained on trajectories of raw and/or encoded parameters across optimization steps, could help capture reusable training dynamics and accelerate model training across tasks, architectures, and settings.
* **Scaling Bottleneck:** We focused specifically on the scaling challenges of parameter-space “warping,” a term nicely suggested by Lucas in reference to warp-drive propulsion: the idea of moving through a model’s training trajectory by making rapid, non-local jumps through parameter space rather than progressing only step by step.
* Topic explored with [Lucas](https://scholar.google.com/citations?user=PHQDcTAAAAAJ&hl=fr), under the guidance of [Damien Scieur](https://scholar.google.com/citations?user=hNscQzgAAAAJ&hl=fr), [Boris Knyazev](https://scholar.google.com/citations?user=Dp9VFB0AAAAJ&hl=en), and [Alexia Jolicoeur-Martineau](https://scholar.google.com/citations?user=0qytQ1oAAAAJ&hl=en).

<div style="height: 0.8rem;"></div>

### ▸ *Selected Graduate Technical Projects* *(2021–2024)*

* **Non-Contrastive SSL Collapse (2023)**: Studied mechanisms preventing representation collapse in SSL.
* **Neural Decoding from M1 (2023, CERVO)**: Built deep learning pipelines for behavior, force, and kinematics decoding.
* **Surrogate Models for EM Simulation (2022)**: Learned neural surrogates for magnetic-component simulations.
* **Deep RL for Wood Drying (2022)**: Built a PPO simulator for industrial process optimization.
* **Neural Combinatorial Optimization (2022)**: Applied graph neural networks and RL to weapon-target assignment.
* **Superconducting Critical Temperature Prediction (2021)**: Predicted material critical temperatures with neural networks.
* **Model-Free vs. Model-Based RL**: Studied planning-based RL methods, including MuZero.
* **ML Theory Notebooks (2020)**: Built notebooks combining ML theory, statistics, and Python.

<div style="height: 0.8rem;"></div>

### ▸ *Algorithmic Trading and Investment Automation Platform* *(2020–Present)*

* **Overview:** Developed algorithms and a prototype platform for automating and sharing investment strategies across asset classes, allowing users to allocate part of their portfolio to strategies they created or strategies made available by other users.
* **State:** The project is still active: DM if interested or want more information!
