---
title: "MagicAgent: Towards Generalized Agent Planning"
collection: publications
pub_category: agents
permalink: /publication/magicagent
excerpt: 'MagicAgent is a series of foundation models for generalized agent planning, trained with scalable synthetic planning trajectories and a two-stage SFT plus multi-objective RL paradigm.'
excerpt_zh: 'MagicAgent 研究面向真实数字环境的通用智能体能力，强调在多步骤任务中理解环境、调用工具并根据反馈持续调整行动。论文围绕智能体任务构建、评测和能力提升展开，服务于更稳定的 GUI 与工具使用智能体。'
date: 2026-02-22
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2602.19000'
citation: 'Xuhui Ren, Shaokang Dong, Chen Yang, Qing Gao, Yunbin Zhao, Yongsheng Liu, Xinwei Geng, Xiang Li, Demei Yan, Yanqing Li, Chenhao Huang, Dingwei Zhu, Junjie Ye, Boxuan Yue, Yingnan Fu, Mengzhe Lv, Zezeng Feng, Boshen Zhou, Bocheng Wang, Xuanjing Huang, Yu-Gang Jiang, Tao Gui, Qi Zhang, Yunke Zhang. MagicAgent: Towards Generalized Agent Planning. arXiv:2602.19000, 2026.'
lang: en
---
The evolution of Large Language Models (LLMs) from passive text processors to autonomous agents has established planning as a core component of modern intelligence. However, achieving generalized planning remains elusive, not only by the scarcity of high-quality interaction data but also by inherent conflicts across heterogeneous planning tasks. These challenges result in models that excel at isolated tasks yet struggle to generalize, while existing multi-task training attempts suffer from gradient interference. In this paper, we present \textbf{MagicAgent}, a series of foundation models specifically designed for generalized agent planning. We introduce a lightweight and scalable synthetic data framework that generates high-quality trajectories across diverse planning tasks, including hierarchical task decomposition, tool-augmented planning, multi-constraint scheduling, procedural logic orchestration, and long-horizon tool execution. To mitigate training conflicts, we propose a two-stage training paradigm comprising supervised fine-tuning followed by multi-objective reinforcement learning over both static datasets and dynamic environments. Empirical results show that MagicAgent-32B and MagicAgent-30B-A3B achieve superior performance across diverse open-source benchmarks (\emph{e.g.}, $75.1\%$ on Worfbench and $86.9\%$ on BFCL-v3), as well as strong results on our in-house MagicEval benchmarks, substantially outperforming existing sub-100B models and surpassing leading ultra-scale models, including GPT-5.2, Kimi-K2 and GLM-4.7.

[Download paper here](https://arxiv.org/abs/2602.19000)
