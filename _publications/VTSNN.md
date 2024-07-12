---
title: "VTSNN: a virtual temporal spiking neural network"
collection: publications
permalink: /publication/VTSNN
excerpt: 'Spiking neural networks (SNNs) have recently demonstrated outstanding performance in a variety of high-level tasks, such as image classification. However, advancements in the field of low-level assignments, such as image reconstruction, are rare. This may be due to the lack of promising image encoding techniques and corresponding neuromorphic devices designed specifically for SNN-based low-level vision problems. This paper begins by proposing a simple yet effective undistorted weighted-encoding-decoding technique, which primarily consists of an Undistorted Weighted-Encoding (UWE) and an Undistorted Weighted-Decoding (UWD). The former aims to convert a gray image into spike sequences for effective SNN learning, while the latter converts spike sequences back into images. Then, we design a new SNN training strategy, known as Independent-Temporal Backpropagation (ITBP) to avoid complex loss propagation in spatial and temporal dimensions, and experiments show that ITBP is superior to Spatio-Temporal Backpropagation (STBP). Finally, a so-called Virtual Temporal SNN (VTSNN) is formulated by incorporating the above-mentioned approaches into U-net network architecture, fully utilizing the potent multiscale representation capability. Experimental results on several commonly used datasets such as MNIST, F-MNIST, and CIFAR10 demonstrate that the proposed method produces competitive noise-removal performance extremely which is superior to the existing work. Compared to ANN with the same architecture, VTSNN has a greater chance of achieving superiority while consuming ~1/274 of the energy. Specifically, using the given encoding-decoding strategy, a simple neuromorphic circuit could be easily constructed to maximize this low-carbon strategy.'
date: 2023-05-23
venue: 'GitHub Journal of Bugs'
paperurl: 'https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2023.1091097/full'
citation: 'Qiu X R, Wang Z R, Luan Z, et al. VTSNN: a virtual temporal spiking neural network[J]. Frontiers in neuroscience, 2023, 17: 1091097.'
---

