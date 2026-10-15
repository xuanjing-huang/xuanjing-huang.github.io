---
title: "AgentGym-RL: An Open-Source Framework to Train LLM Agents for Long-Horizon Decision Making via Multi-Turn RL"
collection: publications
pub_category: agents
permalink: /publication/agentgym-rl
excerpt: 'We propose AgentGym-RL, an open-source, modular framework for training LLM agents from scratch with multi-turn reinforcement learning across diverse real-world environments, together with ScalingInter-RL, a staged training approach for stable long-horizon RL.'
date: 2026-04-23
venue: 'International Conference on Learning Representations (ICLR 2026), Oral'
paperurl: 'https://openreview.net/forum?id=ZgCCDwcGwn'
citation: 'Zhiheng Xi, Jixuan Huang, Chenyang Liao, Baodai Huang, Jiaqi Liu, Honglin Guo, Yajie Yang, Rui Zheng, Junjie Ye, Jiazheng Zhang, Wenxiang Chen, Wei He, Yiwen Ding, Guanyu Li, Zehui Chen, Zhengyin Du, Xuesong Yao, Yufei Xu, Jiecao Chen, Tao Gui, Zuxuan Wu, Qi Zhang, Xuanjing Huang, Yu-Gang Jiang. AgentGym-RL: An Open-Source Framework to Train LLM Agents for Long-Horizon Decision Making via Multi-Turn RL. ICLR 2026 (Oral).'
lang: en
---
Training LLM agents for complex multi-turn decision-making tasks requires extensive exploration within their environment, with reinforcement learning (RL) as a natural way. However, the open-source community currently lacks a unified RL framework capable of training agents from scratch across diverse and realistic environments. To bridge this gap, we introduce AgentGym-RL, a modular and decoupled framework specifically designed for RL-based agent in multi-turn decision-making tasks. It offers high flexibility and extensibility, supports mainstream RL algorithms, and spans a broad range of real-world scenarios. To effectively train agents for challenging tasks, we argue that they are required to expand external interactions with the environment, rather than relying solely on internal reasoning. Nevertheless, training agents for long-horizon interaction with vanilla methods often faces challenges like training instability. To this end, we propose ScalingInter-RL, a staged training approach for stable long-horizon RL training. It starts with short-horizon interaction to establish foundational policies and progressively expands them to encourage deeper exploration. Extensive experiments show that agents trained with our method achieve performance on par with—or even surpass—commercial counterparts like OpenAI o3 and Gemini-2.5-Pro across 27 tasks in diverse environments. We share key insights and release the full framework, including code and datasets, to empower the community in building the next generation of intelligent agents. Our framework is available at https://github.com/WooooDyy/AgentGym-RL.

[Download paper here](https://openreview.net/forum?id=ZgCCDwcGwn) · [arXiv](https://arxiv.org/abs/2509.08755)
