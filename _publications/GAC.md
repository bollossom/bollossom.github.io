---
title: "Gated attention coding for training high-performance and efficient spiking neural networks"
collection: publications
permalink: /publications/GAC
excerpt: "Spiking neural networks (SNNs) are emerging as an energy-efficient alternative to traditional artificial neural networks (ANNs) due to their unique spike-based event-driven nature. Coding is crucial in SNNs as it converts external input stimuli into spatio-temporal feature sequences. However, most existing deep SNNs rely on direct coding that generates powerless spike representation and lacks the temporal dynamics inherent in human vision. Hence, we introduce Gated Attention Coding (GAC), a plug-and-play module that leverages the multi-dimensional gated attention unit to efficiently encode inputs into powerful representations before feeding them into the SNN architecture. GAC functions as a preprocessing layer that does not disrupt the spike-driven nature of the SNN, making it amenable to efficient neuromorphic hardware implementation with minimal modifications. Through an observer model theoretical analysis, we demonstrate GAC's attention mechanism improves temporal dynamics and coding efficiency. Experiments on CIFAR10/100 and ImageNet datasets demonstrate that GAC achieves state-of-the-art accuracy with remarkable efficiency. Notably, we improve top-1 accuracy by 3.10% on CIFAR100 with only 6-time steps and 1.07% on ImageNet while reducing energy usage to 66.9% of the previous works. To our best knowledge, it is the first time to explore the attention-based dynamic coding scheme in deep SNNs, with exceptional effectiveness and efficiency on large-scale datasets."
date: 2024-3-25
venue: 'AAAI 2024 Poster'
paperurl: 'https://ojs.aaai.org/index.php/AAAI/article/view/27816'
citation: 'Qiu X, Zhu R J, Chou Y, et al. Gated attention coding for training high-performance and efficient spiking neural networks. AAAI 2024.'
---
