---
title: "High-Performance Temporal Reversible Spiking Neural Networks with O(L) Training Memory and O(1) Inference Cost"
collection: publications
permalink: /publication/T-RevSNN
excerpt: 'Multi-timestep simulation of brain-inspired Spiking Neural Networks (SNNs) boost memory requirements during training and increase inference energy cost. Current training methods cannot simultaneously solve both training and inference dilemmas. This work proposes a novel Temporal Reversible architecture for SNNs (T-RevSNN) to jointly address the training and inference challenges by altering the forward propagation of SNNs. We turn off the temporal dynamics of most spiking neurons and design multi-level temporal reversible interactions at temporal turn-on spiking neurons, resulting in a O(L) training memory. Combined with the temporal reversible nature, we redesign the input encoding and network organization of SNNs to achieve O(1) inference energy cost. Then, we finely adjust the internal units and residual connections of the basic SNN block to ensure the effectiveness of sparse temporal information interaction. T-RevSNN achieves excellent accuracy on ImageNet, while the memory efficiency, training time acceleration, and inference energy efficiency can be significantly improved by 8.6×, 2.0×, and 1.6×, respectively. This work is expected to break the technical bottleneck of significantly increasing memory cost and training time for large-scale SNNs while maintaining high performance and low inference energy cost.'
date: 2024-06-25
venue: 'ICML 2024 Spotlight'
paperurl: 'https://openreview.net/forum?id=s4h6nyjM9H'
citation: 'Hu J K, Yao M, Qiu X, et al. High-Performance Temporal Reversible Spiking Neural Networks with O(L) Training Memory and O(1) Inference Cost[C]. ICML 2024.'
---


