---
title: "A Lexicon-Based Graph Neural Network for Chinese NER"
collection: publications
permalink: /publication/ALB
excerpt: 'In this work, we introduce a lexicon-based graph neural network with global semantics for Chinese NER.'
date: 2019-11-03
venue: 'EMNLP/IJCNLP (1) 2019'
paperurl: 'http://xuanjing-huang.github.io/files/ALB.pdf'
citation: 'Tao Gui, Yicheng Zou, Qi Zhang, Minlong Peng, Jinlan Fu, Zhongyu Wei, Xuanjing Huang: A Lexicon-Based Graph Neural Network for Chinese NER. EMNLP/IJCNLP (1) 2019: 1040-1050'
---
Recurrent neural networks (RNN) used for Chinese named entity recognition (NER) that sequentially track character and word information have achieved great success. However, the characteristic of chain structure and the lack of global semantics determine that RNN-based models are vulnerable to word ambiguities. In this work, we try to alleviate this problem by introducing a lexicon-based graph neural network with global semantics, in which lexicon knowledge is used to connect characters to capture the local composition, while a global relay node can capture global sentence semantics and long-range dependency. Based on the multiple graph-based interactions among characters, potential words, and the whole-sentence semantics, word ambiguities can be effectively tackled. Experiments on four NER datasets show that the proposed model achieves significant improvements against other baseline models.

[Download paper here](http://xuanjing-huang.github.io/files/ALB.pdf)