# DuTCh SpaCE: Spatial Reasoning in Multimodal LLMs via CoT Distillation and Monte Carlo Tree Search

![DuTCh SpaCE Overview](https://raw.githubusercontent.com/riccardocampanella/dutch-space/main/assets/dutch-space.jpeg)


> **Exploring spatial reasoning capabilities in state-of-the-art Multimodal LLMs for Dutch building renovation, introducing the DuTCh SpaCE framework to enhance reasoning and reduce hallucinations.**

## 🎯 Interactive Visualization

**[📊 View Live Results →](https://your-username.github.io/dutch-space)**

This repository contains interactive radar charts showcasing the performance of our **DuTCh SpaCE** framework across 13 architectural features using multiple evaluation metrics.

## 📋 Table of Contents

- [Overview](#overview)
- [Key Achievements](#key-achievements)

## 🔬 Overview

### Abstract

In this exploratory work, we investigate the spatial reasoning capabilities of state-of-the-art Multimodal Large Language Models (MLLMs) in the context of building renovation. We evaluate models with different capacities, including GPT-4o, Qwen, Mulberry, and SpatialRGPT on a few-shot dataset of Dutch residential buildings, assessing their performance in visual reasoning tasks.

We propose **DuTCh SpaCE**, a novel application of Chain-of-Thought Distillation consisting of a Dual-Teacher Framework that leverages both step-by-step rationales and scene graph description augmentation to guide and assess student models' performance on spatial reasoning. This structured supervision enables iterative refinement of spatial reasoning through domain-task decomposition and scene understanding.

Additionally, we integrate Monte Carlo Tree Search at inference time to improve reasoning-path selection under visual uncertainty. By combining distillation and MCTS, we observe a measurable reduction in hallucinations, with models generating more grounded and verifiable predictions.

### Research Title
**"Spatial Reasoning in Multimodal LLMs via CoT Distillation and Monte Carlo Tree Search for Dutch Facade-Element Detection"**

## 🏆 Key Achievements

| Achievement | Description |
|-------------|-------------|
| **🔬 Chain-of-Thought Distillation** | Novel dual-teacher framework with step-by-step rationales and scene graph augmentation |
| **✨ Reduced Hallucinations** | Measurable reduction in false predictions through structured supervision |
| **🎯 MCTS Integration** | Monte Carlo Tree Search for improved reasoning-path selection under visual uncertainty |
| **📈 Scalable Framework** | Domain-specific spatial reasoning without extensive visual grounding requirements |


### Key Findings

- **Consistent Performance**: DCoT and DCoT+Scene show identical results, indicating optimal baseline performance
- **Architectural Excellence**: Strong performance on structural elements (balconies, weep holes, chimneys)
- **Reliable Detection**: Stable performance across multiple architectural features
- **Framework Effectiveness**: Chain-of-Thought distillation proves effective for spatial reasoning tasks
