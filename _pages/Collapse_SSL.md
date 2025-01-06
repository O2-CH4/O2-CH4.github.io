---
layout: archive
title: ""
permalink: /Collapse_SSL/
author_profile: true
---


## Avoiding Collapses in Non-Contrastive SSL Methods [PDF](https://o2-ch4.github.io/files/Report_SSL.pdf) 

- **Context**: Theoretical Principles for Deep Learning (Graduate Course) (UdeM/Mila)

- **Overview**: Non-Contrastive Self-Supervised Learning is considered as a potential training paradigm for acquiring large sets of prior knowledge from unlabeled multi-modal data. This could allow future AI agents to acquire a grounded understanding of their environnement and System-2 reasoning capabilities. To that end, I decided to investigate some properties of recent non-contrastive methods, more specifically how are they maximizing the information content of their representations in order to avoid different types of collapses.

- **Details**: Recent self-supervised learning methods for image representation are either classified as contrastive or non-contrastive. Contrastive methods operate by simultaneously minimizing the distance between two augmented views of the same data point (positive pairs) and maximizing views from different data points (negative pairs). While those techniques achieve state of the art results for image classification with few labeled samples, their use of negative pairs is making them limited in many aspects as their scaling potential is limited by the ability of finding suitable contrastive samples for training. Recently, many Non-Contrastive methods have shown competitive results without using any negative pairs, which raises the question of how those methods avoid any type of collapsing solutions to their loss function? Driven by those recent advances, the goal of this project report was to study in detail how and why some recent non-contrastive methods avoid any type of collapses via some specific architectural changes and regularization to their loss functions. In other words, how those methods can avoid trivial solutions that output constant solutions while keeping a high information content in their representations.



---

