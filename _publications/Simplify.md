---
title: "Simplify the Usage of Lexicon in Chinese NER"
collection: publications
permalink: /publication/Simplify
excerpt: 'In this work, we propose a simple but effective method for incorporating the word lexicon into the character representations.'
date: 2020-07-05
venue: 'Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics'
paperurl: 'http://xuanjing-huang.github.io/files/Simplify.pdf'
citation: 'Ruotian Ma, Minlong Peng, Qi Zhang, Zhongyu Wei, Xuanjing Huang: Simplify the Usage of Lexicon in Chinese NER. ACL 2020: 5951-5960'
---
Recently, many works have tried to augment the performance of Chinese named entity recognition (NER) using word lexicons. As a representative, Lattice-LSTM (Zhang and Yang, 2018) has achieved new benchmark results on several public Chinese NER datasets. However, Lattice-LSTM has a complex model architecture. This limits its application in many industrial areas where real-time NER responses are needed. In this work, we propose a simple but effective method for incorporating the word lexicon into the character representations. This method avoids designing a complicated sequence modeling architecture, and for any neural NER model, it requires only subtle adjustment of the character representation layer to introduce the lexicon information. Experimental studies on four benchmark Chinese NER datasets show that our method achieves an inference speed up to 6.15 times faster than those of state-of-the-art methods, along with a better performance. The experimental results also show that the proposed method can be easily incorporated with pre-trained models like BERT. 


[Download paper here](http://xuanjing-huang.github.io/files/Simplify.pdf)
