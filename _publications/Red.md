---
title: "Advancing Parameter Efficiency in Fine-tuning via Representation Editing"
collection: publications
permalink: /publications/Red
excerpt: "Parameter Efficient Fine-Tuning (PEFT) has gained significant attention for its ability to achieve competitive results while updating only a small subset of trainable parameters. Despite the promising performance of current PEFT methods, they present challenges in hyperparameter selection, such as determining the rank of LoRA or Adapter, or specifying the length of soft prompts. In addressing these challenges, we propose a novel approach to fine-tuning neural models, termed Representation EDiting (RED), which scales and biases the representation produced at each layer. RED substantially reduces the number of trainable parameters by a factor of 25,700 compared to full parameter fine-tuning, and by a factor of 32 compared to LoRA. Remarkably, RED achieves comparable or superior results to full parameter fine-tuning and other PEFT methods. Extensive experiments were conducted across models of varying architectures and scales, including RoBERTa, GPT-2, T5, and Llama-2, and the results demonstrate the efficiency and efficacy of RED, positioning it as a promising PEFT approach for large neural models."
date: 2024-02-29
venue: 'ACL'
paperurl: 'https://arxiv.org/pdf/2402.15179.pdf'
citation: "Wu M, Liu W, Wang X, et al. Advancing Parameter Efficiency in Fine-tuning via Representation Editing[J]. ACL 2024, Main."
---

[Download paper here](https://arxiv.org/pdf/2402.15179.pdf)
