---
title: "Scaling Verifiable Environments for Long-horizon Work Agents"
collection: publications
pub_category: agents
permalink: /publication/workforge
excerpt: 'WorkForge is a scalable framework that builds verifiable work-agent environments from real-world resources, deriving tasks and programmatic and semantic verifiers from factual anchors in each workspace.'
date: 2026-10-04
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2610.04906'
citation: 'Jiazheng Zhang, Long Ma, Yunxian Yang, Zhiheng Xi, Zhikai Lei, Yajie Yang, Chenyang Liao, Enyu Zhou, Yang Nan, Yuchen Tian, Senjie Jin, Yibo Wang, Wei He, Boyang Liu, Jixuan Huang, Xin Guo, Shutong Jiang, Zhezheng Hao, Xinbing Liang, Zhihao Zhang, Changzhi Zhou, Wiggin Zhou, Tao Gui, Qi Zhang, Xuanjing Huang, et al. Scaling Verifiable Environments for Long-horizon Work Agents. arXiv:2610.04906, 2026.'
lang: en
---
Work agents operate over digital artifacts to execute professional knowledge-intensive work, requiring training environments that support long-horizon interaction and trustworthy verification. However, hand-crafted environments incur prohibitive engineering overhead that prevents environment scaling, whereas synthesis methods sacrifice workspace complexity, realism, or grounded verifiability. To bridge this gap, we introduce WorkForge, a scalable synthesis framework for constructing verifiable work-agent environments from real-world resources. Starting from expert workflows, WorkForge first identifies the resources, decisions, and deliverables required by each workflow. It then retrieves relevant real-world files and organizes them into a workspace. WorkForge inspects the workspace to extract concrete, checkable facts about its content. These factual anchors fix which task types the workspace can support and how their outcomes can be verified. Therefore, WorkForge derives each task's instructions, solution plan, and complementary programmatic and semantic verifiers directly from these factual anchors, keeping verification traceable to observable workspace evidence. Furthermore, we construct 16.7K verifiable environments across 40 professional domains, with workspaces collectively covering 60 file types. Post-training Qwen3.5-35B-A3B-Base improves GDPVal from 45.5 to 73.6 and APEX Score from 5.0 to 21.3, while enabling Qwen3.5-27B to achieve highly competitive performance and outperform strong competitors. Our analyses confirm the efficacy of the proposed method and reveal consistent scaling behaviors across both data volume and interaction horizons.

[Download paper here](https://arxiv.org/abs/2610.04906)
