---
title: "Secrets of RLHF in Large Language Models Part I: PPO"
collection: publications
permalink: /publication/rlhf
excerpt: 'We dissect the framework of RLHF, re-evaluate the inner workings of PPO, and explore how the parts comprising PPO algorithms impact policy agent training.'
date: 2023-07-01
venue: 'CoRR abs/2307.04964'
paperurl: 'http://xuanjing-huang.github.io/files/rlhf.pdf'
citation: 'Rui Zheng, Shihan Dou, Songyang Gao, Yuan Hua, Wei Shen, Binghai Wang, Yan Liu, Senjie Jin, Qin Liu, Yuhao Zhou, Limao Xiong, Lu Chen, Zhiheng Xi, Nuo Xu, Wenbin Lai, Minghao Zhu, Cheng Chang, Zhangyue Yin, Rongxiang Weng, Wensen Cheng, Haoran Huang, Tianxiang Sun, Hang Yan, Tao Gui, Qi Zhang, Xipeng Qiu, Xuanjing Huang: Secrets of RLHF in Large Language Models Part I: PPO. CoRR abs/2307.04964 (2023)'
---
Large language models (LLMs) have formulated a blueprint for the advancement of artificial general intelligence. Its primary objective is to function as a humancentric (helpful, honest, and harmless) assistant. Alignment with humans assumes paramount significance, and reinforcement learning with human feedback (RLHF) emerges as the pivotal technological paradigm underpinning this pursuit. Current technical routes usually include reward models to measure human preferences, Proximal Policy Optimization (PPO) to optimize policy model outputs, and process supervision to improve step-by-step reasoning capabilities. However, due to the challenges of reward design, environment interaction, and agent training, coupled with huge trial and error cost of large language models, there is a significant barrier for AI researchers to motivate the development of technical alignment and safe landing of LLMs. The stable training of RLHF has still been a puzzle. 

In the first report, we dissect the framework of RLHF, re-evaluate the inner workings of PPO, and explore how the parts comprising PPO algorithms impact policy agent training. We identify policy constraints being the key factor for the effective implementation of the PPO algorithm. Therefore, we explore the PPO-max, an advanced version of PPO algorithm, to efficiently improve the training stability of the policy model. Based on our main results, we perform a comprehensive analysis of RLHF abilities compared with SFT models and ChatGPT. Beyond additional qualitative results, we even find that LLMs successfully trained by our algorithm can often better understand the deep meaning of the queries, and its responses are more able to hit people’s souls directly. The absence of open-source implementations has posed significant challenges to the investigation of LLMs alignment.

[Download paper here](http://xuanjing-huang.github.io/files/rlhf.pdf)
