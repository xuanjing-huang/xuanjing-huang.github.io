---
title: "MagicGUI: A Foundational Mobile GUI Agent with Scalable Data Pipeline and Reinforcement Fine-tuning"
collection: publications
pub_category: agents
permalink: /publication/magicgui
excerpt: 'MagicGUI is a foundational mobile GUI agent built on a scalable GUI data pipeline, a unified action space, planning-oriented reasoning, and two-stage training combining continued pre-training with reinforcement fine-tuning.'
excerpt_zh: 'MagicGUI 面向图形用户界面智能体，研究如何让模型理解屏幕内容、执行操作并完成真实软件环境中的任务。论文关注 GUI 任务中的感知、规划与交互，为构建更可靠的桌面和移动端智能体提供基准与方法。'
date: 2025-07-19
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2508.03700'
citation: 'Liujian Tang, Shaokang Dong, Yijia Huang, Minqi Xiang, Hongtao Ruan, Bin Wang, Shuo Li, Zhiheng Xi, Zhihui Cao, Hailiang Pang, Heng Kong, He Yang, Mingxu Chai, Zhilin Gao, Xingyu Liu, Yingnan Fu, Jiaming Liu, Xuanjing Huang, Yu-Gang Jiang, Tao Gui, Qi Zhang, Kang Wang, Yunke Zhang, Yuran Wang. MagicGUI: A Foundational Mobile GUI Agent with Scalable Data Pipeline and Reinforcement Fine-tuning. arXiv:2508.03700, 2025.'
lang: en
---
This paper presents MagicGUI, a foundational mobile GUI agent designed to address critical challenges in perception, grounding, and reasoning within real-world mobile GUI environments. The framework is underpinned by following six key components: (1) a comprehensive and accurate dataset, constructed via the scalable GUI Data Pipeline, which aggregates the largest and most diverse GUI-centric multimodal data to date from open-source repositories, automated crawling, and targeted manual annotation; (2) enhanced perception and grounding capabilities, facilitating fine-grained multimodal alignment for UI element referencing, grounding, and screen comprehension; (3) a comprehensive and unified action space, encompassing both fundamental UI operations and complex interactive intents to support human-agent interactions; (4) planning-oriented reasoning mechanisms that enable the model to decompose complex user instructions into sequential actions with explicit intermediate meta-paln reasoning; (5) an iterative two-stage training procedure, combining large-scale continue pre-training on 7.8M samples with reinforcement fine-tuning utilizing a spatially enhanced composite reward and dual filtering strategy; and (6) competitive performance on both the proprietary Magic-RICH benchmark and over a dozen public benchmarks, achieving superior performance across GUI perception and agent tasks, while demonstrating robust generalization and real-world deployment potential in practical mobile GUI scenarios, as detailed in Figure 1.

[Download paper here](https://arxiv.org/abs/2508.03700)
