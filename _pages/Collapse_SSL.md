---
layout: archive
title: ""
permalink: /Collapse_SSL/
author_profile: true
---


## Avoiding Collapses in Non-Contrastive SSL Methods [(PDF)](https://o2-ch4.github.io/files/Report_SSL.pdf) 

- **Context**: Theoretical Principles for Deep Learning (Graduate Course, UdeM/Mila)

- **Overview**: Non-Contrastive Self-Supervised Learning is emerging as a promising paradigm for acquiring prior knowledge from large quantities of unlabeled multi-modal data. This approach could enable future AI agents to gain a grounded understanding of their environment and System-2 reasoning capabilities. For this project, I investigated the properties of recent non-contrastive methods, focusing on how they maximize the information content of their representations to prevent various forms of collapse.

- **Details**: Recent self-supervised learning methods for image representation can be classified as either contrastive or non-contrastive. Contrastive methods minimize the distance between augmented views of the same data point (positive pairs) while maximizing the distance between views from different data points (negative pairs). While effective for image classification with limited labeled data, these methods face scalability challenges due to the reliance on suitable contrastive samples. Non-contrastive methods, on the other hand, achieve competitive results without using negative pairs, raising the question of how they avoid collapsing solutions in their loss functions. This project aimed to explore in detail how recent non-contrastive methods prevent collapse through specific architectural choices and regularization techniques, ensuring high information content in their learned representations.


---
