---
layout: archive
title: ""
permalink: /Neural_Solver/
author_profile: true
---


## Neural Solver for Weapon-Target Assignments: A Deep-RL Approach [(PDF)](https://o2-ch4.github.io/files/WTA_Report.pdf) 

- **Overview**: Together with two other students, I conducted a project examining the trade-offs involved in using end-to-end neural solvers compared to traditional methods for solving combinatorial optimization problems

- **Details**: Neural solvers approximate or learn an end-to-end policy that takes a problem instance as input and directly outputs a solution, ideally optimizing the desired objective function(s) while adhering to constraints. These problems can be permutation-based or assignment-based. In our work, we focused on comparing the performance of a Graph Attention Neural Network (GAT) architecture and a traditional solver on a specific assignment problem: the Weapon-Target Assignment (WTA). This defense-related problem involves assigning interceptors or missiles from different weapon systems to targets to minimize the total expected destructive value of incoming threats. We used reinforcement learning to train our neural solver to learn an optimal policy, with the reward being the negative of the total expected destructive value of all targets post-assignment. If supervised learning had been used, the optimal policy could be said to be approximated. At inference time, solutions were generated autoregressively by our model.


---


