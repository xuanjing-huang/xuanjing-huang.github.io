---
title: "Agentic Harness Engineering: Observability-Driven Automatic Evolution of Coding-Agent Harnesses"
collection: publications
pub_category: agents
permalink: /publication/agentic-harness-engineering
excerpt: 'We introduce Agentic Harness Engineering (AHE), an observability-driven closed loop that automatically evolves coding-agent harnesses, lifting Terminal-Bench 2 pass@1 from 69.7% to 77.0% and surpassing the human-designed Codex-CLI harness.'
excerpt_zh: 'Agentic Harness Engineering（AHE）让编程智能体自动演化自身 harness：它把可编辑组件、海量轨迹证据和每次修改的预期效果都显式化，使 harness 迭代可以被观察和验证。经过 10 轮自动演化，Terminal-Bench 2 通过率从 69.7% 提升到 77.0%，并可迁移到 SWE-bench Verified 和其他模型系列。'
date: 2026-04-28
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2604.25850'
citation: 'Jiahang Lin, Shichun Liu, Chengjun Pan, Lizhi Lin, Shihan Dou, Zhiheng Xi, Xuanjing Huang, Hang Yan, Zhenhua Han, Tao Gui, Yu-Gang Jiang. Agentic Harness Engineering: Observability-Driven Automatic Evolution of Coding-Agent Harnesses. arXiv:2604.25850, 2026.'
lang: en
---
Harnesses are now central to coding-agent performance, mediating how models interact with tools and execution environments. Yet harness engineering remains a manual craft, because automating it faces a heterogeneous action space across editable components, voluminous trajectories that bury actionable signal, and edits whose effect is hard to attribute. We introduce Agentic Harness Engineering (AHE), a closed loop that addresses these challenges through three matched observability pillars: (1) component observability gives every editable harness component a file-level representation so the action space is explicit and revertible; (2) experience observability distills millions of raw trajectory tokens into a layered, drill-down evidence corpus that an evolving agent can actually consume; and (3) decision observability pairs every edit with a self-declared prediction, later verified against the next round's task-level outcomes. Together, these pillars turn every edit into a falsifiable contract, so harness evolution proceeds autonomously without collapsing into trial-and-error. Empirically, ten AHE iterations lift pass@1 on Terminal-Bench 2 from 69.7% to 77.0%, surpassing the human-designed harness Codex-CLI (71.9%) and the self-evolving baselines ACE and TF-GRPO. The frozen harness transfers without re-evolution: on SWE-bench-verified it tops aggregate success at 12% fewer tokens than the seed, and on Terminal-Bench 2 it yields +5.1 to +10.1pp cross-family gains across three alternate model families, indicating the evolved components encode general engineering experience rather than benchmark-specific tuning. Ablations localize the gain to tools, middleware, and long-term memory rather than the system prompt, suggesting factual harness structure transfers while prose-level strategy does not.

[Download paper here](https://arxiv.org/abs/2604.25850)
