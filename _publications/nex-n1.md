---
title: "Nex-N1: Agentic Models Trained via a Unified Ecosystem for Large-Scale Environment Construction"
collection: publications
pub_category: agents
permalink: /publication/nex-n1
excerpt: 'Nex-N1 is an agentic model trained on a unified ecosystem that scales the complexity, diversity, and fidelity of interactive environments, with open-sourced framework and model weights.'
excerpt_zh: 'Nex-N1 面向大语言模型的复杂推理能力，通过过程监督与强化学习相结合的方法提升模型在数学、代码和通用推理任务上的表现。论文围绕可扩展训练流程、奖励建模和推理能力提升展开，是团队在下一代推理模型方向上的代表性工作。'
date: 2025-12-04
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2512.04987'
citation: 'Nex-AGI Team (Yuxuan Cai, Lu Chen, Qiaoling Chen, et al., including Xuanjing Huang). Nex-N1: Agentic Models Trained via a Unified Ecosystem for Large-Scale Environment Construction. arXiv:2512.04987, 2025.'
lang: en
---
The evolution of Large Language Models (LLMs) from passive responders to autonomous agents necessitates a fundamental shift in learning paradigms -- from static imitation to incentive-driven decision making. However, this transition is significantly impeded by the lack of scalable infrastructure capable of constructing high-quality interaction signals for effective policy learning. To address this, we introduce a comprehensive method designed to systematically scale the diversity and complexity of interactive environments. Our method realizes this scaling by addressing three orthogonal dimensions: (1) Complexity: NexAU, a flexible agent framework that supports building complex agent hierarchies via simple configurations; (2) Diversity: NexA4A automatically generates diverse agent hierarchies from natural language to cover infinite domains; and (3) Fidelity: NexGAP bridges the simulation-reality gap by integrating dynamic real-world environment for grounded trajectories synthesis. We train Nex-N1 upon the diverse and complex interactive environments established by our infrastructure. Empirical results on benchmarks such as SWE-bench and tau2 demonstrate that Nex-N1 consistently outperforms SOTA open-source models and achieves competitive performance against frontier proprietary models on complex agentic tasks. We open-source the Nex ecosystem and model weights to facilitate further research.

[Download paper here](https://arxiv.org/abs/2512.04987)
