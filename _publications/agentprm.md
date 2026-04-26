---
title: "AgentPRM: Process Reward Models for LLM Agents via Step-Wise Promise and Progress"
collection: publications
permalink: /publication/agentprm
excerpt: 'We propose AgentPRM, a re-defined process reward model for LLM agent tasks that captures both the interdependence between sequential decisions and their contribution to the final goal, enabling better progress tracking and exploration-exploitation balance.'
date: 2026-04-28
venue: 'The ACM Web Conference 2026 (WWW 2026)'
paperurl: 'https://arxiv.org/abs/2511.08325'
citation: 'Zhiheng Xi, Chenyang Liao, Guanyu Li, Yajie Yang, Wenxiang Chen, Zhihao Zhang, Bing Wang, Senjie Jin, Yuhao Zhou, Jian Guan, Wei Wu, Tao Ji, Tao Gui, Qi Zhang, Xuanjing Huang. AgentPRM: Process Reward Models for LLM Agents via Step-Wise Promise and Progress. In Proceedings of the ACM Web Conference 2026 (WWW 2026).'
lang: en
---
Despite rapid development, large language models (LLMs) still encounter challenges in multi-turn decision-making tasks (i.e., agent tasks) like web shopping and browser navigation, which require making a sequence of intelligent decisions based on environmental feedback. Previous work for LLM agents typically relies on elaborate prompt engineering or fine-tuning with expert trajectories to improve performance. In this work, we take a different perspective: we explore constructing process reward models (PRMs) to evaluate each decision and guide the agent's decision-making process. Unlike LLM reasoning, where each step is scored based on correctness, actions in agent tasks do not have a clear-cut correctness. Instead, they should be evaluated based on their proximity to the goal and the progress they have made. Building on this insight, we propose a re-defined PRM for agent tasks, named AgentPRM, to capture both the interdependence between sequential decisions and their contribution to the final goal. This enables better progress tracking and exploration-exploitation balance. To scalably obtain labeled data for training AgentPRM, we employ a Temporal Difference-based (TD-based) estimation method combined with Generalized Advantage Estimation (GAE), which proves more sample-efficient than prior methods. Extensive experiments across different agentic tasks show that AgentPRM is over 8× more compute-efficient than baselines, and it demonstrates robust improvement when scaling up test-time compute.

[Download paper here](https://arxiv.org/abs/2511.08325)
