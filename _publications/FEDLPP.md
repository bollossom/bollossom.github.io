---
title: "Promoting Data and Model Privacy in Federated Learning through Quantized LoRA"
collection: preprint
permalink: /publications/FEDLPP
excerpt: "Conventional federated learning primarily aims to secure the privacy of data distributed across multiple edge devices, with the global model dispatched to edge devices for parameter updates during the learning process. However, the development of large language models (LLMs) requires substantial data and computational resources, rendering them valuable intellectual properties for their developers and owners. To establish a mechanism that protects both data and model privacy in a federated learning context, we introduce a method that just needs to distribute a quantized version of the model's parameters during training. This method enables accurate gradient estimations for parameter updates while preventing clients from accessing a model whose performance is comparable to the centrally hosted one. Moreover, we combine this quantization strategy with LoRA, a popular and parameter-efficient fine-tuning method, to significantly reduce communication costs in federated learning. The proposed framework, named \textsc{FedLPP}, successfully ensures both data and model privacy in the federated learning context. Additionally, the learned central model exhibits good generalization and can be trained in a resource-efficient manner."
date: 2024-06-16
venue: "arxiv"
paperurl: "https://arxiv.org/pdf/2406.10976.pdf"
citation: "Zhu J, Lv C, Wang X, et al. Promoting Data and Model Privacy in Federated Learning through Quantized LoRA[J]. arXiv preprint arXiv:2406.10976, 2024."
---

[Download paper here](https://arxiv.org/pdf/2406.10976.pdf)
