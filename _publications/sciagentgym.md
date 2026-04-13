---
title: "SciAgentGym: Benchmarking Multi-Step Scientific Tool-use in LLM Agents"
collection: publications
permalink: /publication/sciagentgym-zh
excerpt: '我们提出了SciAgentGym，一个可扩展的交互环境，包含跨4个自然学科的1780个领域特定工具，并配有强大的执行基础设施。'
date: 2026-02-13
venue: 'ArXiv'
paperurl: 'https://arxiv.org/pdf/2602.12984'
citation: 'Yujiong Shen, Yajie Yang, Zhiheng Xi, Binze Hu, Huayu Sha, Jiazheng Zhang, Qiyuan Peng, Junlin Shang, Jixuan Huang, Yutao Fan, Jingqi Tong, Shihan Dou, Ming Zhang, Lei Bai, Zhenfei Yin, Tao Gui, Xingjun Ma, Qi Zhang, Xuanjing Huang, Yu-Gang Jiang: SciAgentGym: Benchmarking Multi-Step Scientific Tool-use in LLM Agents. ArXiv 2602.12984 (2026)'
lang: zh
---

科学推理本质上需要整合复杂的工具包来导航领域特定知识。然而，当前的基准测试在很大程度上忽视了对这类严格工作流程进行工具编排的智能体能力。为了弥补这一差距，我们提出了SciAgentGym，这是一个可扩展的交互环境，包含跨四个自然学科的1780个领域特定工具，并配有强大的执行基础设施。作为补充，我们提出了SciAgentBench，这是一个分层评估套件，旨在测试从基本动作到长时域工作流程的智能体能力。我们的评估发现了一个关键瓶颈：最先进的模型在复杂的科学工具使用方面存在困难。即使对于像GPT-5这样的领先模型，随着交互范围的扩大，成功率也从60.6%急剧下降到30.9%，主要由于多步工作流程执行的失败。为了解决这个问题，我们提出了SciForge，这是一种数据合成方法，将工具动作空间建模为依赖图以生成逻辑感知的训练轨迹。通过在这些轨迹上微调，我们的SciAgent-8B超越了更大的Qwen3-VL-235B-Instruct，同时表现出科学工具使用能力的正向跨领域迁移。这些结果突出了下一代自主科学智能体的前景潜力。

[Download paper here](https://arxiv.org/pdf/2602.12984)
