---
layout: archive
title: ""
permalink: /BCI_Decoding/
author_profile: true
---


## Neural Decoding from Primary Motor Cortex Signals [(PDF)](https://o2-ch4.github.io/files/BCI_B_Decoding.pdf) 

This three-part project focused on decoding neural activity from the primary motor cortex (M1) of rats to extract behavioral, force, and kinematic information. It began as a graduate class project that earned top marks, continued independently during vacation, and culminated in an internship offered to further develop these ideas.


- **Behavior Decoding**: As part of a graduate course in Bioinstrumentation and Biomedical Microsystems, I undertook an ambitious project in collaboration with the lab of Dr. Christian Ethier. This project focused on decoding behavioral information from neural activity recorded from the primary motor cortex (M1) of freely behaving rats. Its utility lies in providing a foundation for training neural decoders for brain-computer interfaces (BCIs) in a wide range of scenarios without relying on the intensive data collection procedures used today. The work involved designing a vision system for synchronized tracking of behaviors and neural data using high-density microelectrode arrays. The collected neural signals were processed into spike trains and paired with video-derived behavioral labels, which were then used to train recurrent neural networks (RNNs) capable of classifying behaviors. This effort also included a detailed analysis of hardware and signal processing techniques critical to neural data acquisition

- **Force Decoding**: Building on the behavioral decoding framework, I investigated the potential to decode applied forces from neural activity in the primary motor cortex (M1) of rats during knob-pressing tasks. In collaboration with Dr. Éthier’s lab, force sensors recorded continuous applied forces, while neural activity was simultaneously captured using a 32-channel microwire array. This project evaluated various long short-term memory (LSTM) architectures and loss formulations to assess their effectiveness in decoding force. Through the development of data processing pipelines and models training, I examined whether the recorded activity in M1 could predict applied forces.

- **Kinematics Decoding**: The last step in this project was to decode kinematics, focusing on extracting movement variables from intracortical neural recordings in the primary motor cortex (M1). To achieve this, I interned in Dr. Ethier’s lab and led the development of an end-to-end data pipeline that integrated signal processing, data transformations based on parameters such as temporal resolution and time bin length, dataset creation, and the training of recurrent neural networks to predict kinematic targets. Markerless 3D pose estimation techniques were employed to align precise kinematic labels with the neural recordings. Although this work focused on single-session models, it represented a first step toward developing generalizable neural decoders capable of adapting across diverse subjects and tasks. Future efforts could explore scaling these models to meet the demands of high-channel-count neural systems, advancing motor decoding for prosthetic control and other applications.



---
