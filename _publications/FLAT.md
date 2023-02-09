---
title: "FLAT: Chinese NER Using Flat-Lattice Transformer"
collection: publications
permalink: /publication/FLAT
excerpt: 'In this paper, we propose FLAT: Flat-LAttice Transformer for Chinese NER, which converts the lattice structure into a flat structure consisting of spans.'
date: 2020-07-05
venue: 'Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics'
paperurl: 'http://xuanjing-huang.github.io/files/FLAT.pdf'
citation: 'Xiaonan Li, Hang Yan, Xipeng Qiu, Xuanjing Huang: FLAT: Chinese NER Using Flat-Lattice Transformer. ACL 2020: 6836-6842'
---
Recently, the character-word lattice structure has been proved to be effective for Chinese named entity recognition (NER) by incorporating the word information. However, since the lattice structure is complex and dynamic, most existing lattice-based models are hard to fully utilize the parallel computation of GPUs and usually have a low inference-speed. In this paper, we propose FLAT: Flat-LAttice Transformer for Chinese NER, which converts the lattice structure into a flat structure consisting of spans. Each span corresponds to a character or latent word and its position in the original lattice. With the power of Transformer and well-designed position encoding, FLAT can fully leverage the lattice information and has an excellent parallelization ability. Experiments on four datasets show FLAT outperforms other lexicon-based models in performance and efficiency.


[Download paper here](http://xuanjing-huang.github.io/files/FLAT.pdf)
