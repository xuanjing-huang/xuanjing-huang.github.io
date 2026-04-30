---
title: "AgentGym-RL: Training LLM Agents for Long-Horizon Decision Making through Multi-Turn Reinforcement Learning"
collection: publications
permalink: /publication/agentgym-rl
excerpt: 'We propose AgentGym-RL, a reinforcement learning framework for training large language model (LLM)-based agents to tackle long-horizon decision-making tasks through multi-turn interactions.'
date: 2025-09-01
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2509.08755'
citation: 'Zhiheng Xi, Yiwen Ding, Wenxiang Chen, Boyang Hong, Honglin Guo, Junzhe Wang, Xin Guo, Dingwen Yang, Chenyang Liao, Wei He, Songyang Gao, Lu Chen, Rui Zheng, Yicheng Zou, Tao Gui, Qi Zhang, Xipeng Qiu, Xuanjing Huang, Zuxuan Wu, Yu-Gang Jiang. AgentGym-RL: Training LLM Agents for Long-Horizon Decision Making through Multi-Turn Reinforcement Learning. arXiv:2509.08755, 2025.'
lang: en
---
Large language models (LLMs) have shown remarkable capabilities in various natural language processing tasks, but training them to act as effective agents for long-horizon decision-making remains challenging. Traditional reinforcement learning (RL) methods often struggle with the sparse rewards and complex state spaces inherent in multi-turn interactions. To address this, we introduce AgentGym-RL, a novel framework that leverages multi-turn reinforcement learning to train LLM-based agents for long-horizon decision-making tasks.

AgentGym-RL extends the AgentGym platform by incorporating a comprehensive RL training pipeline that includes: (1) a diverse set of environments spanning 7 real-world scenarios and 14 distinct tasks, (2) a multi-turn interaction mechanism that allows agents to learn from sequential decisions, (3) a reward shaping strategy that provides meaningful feedback for long-horizon tasks, and (4) an efficient training protocol that balances exploration and exploitation.

Our experiments demonstrate that AgentGym-RL significantly improves agent performance on long-horizon tasks compared to baseline methods. The trained agents achieve state-of-the-art results on benchmark tasks while maintaining sample efficiency. Furthermore, we show that the learned policies transfer effectively to unseen environments, highlighting the generalization capabilities of our approach.

The AgentGym-RL framework represents an important step toward developing more capable and general-purpose AI agents that can handle complex, multi-step decision-making in real-world scenarios. We release our code, environments, and trained models to facilitate further research in this direction.

[Download paper here](https://arxiv.org/abs/2509.08755)