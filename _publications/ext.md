---
title: "Extractive Summarization as Text Matching"
collection: publications
permalink: /publication/ext
excerpt: 'This paper creates a paradigm shift with regard to the way we build neural extractive summarization systems.'
date: 2020-07-05
venue: 'Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics'
paperurl: 'http://xuanjing-huang.github.io/files/ext.pdf'
citation: 'Ming Zhong, Pengfei Liu, Yiran Chen, Danqing Wang, Xipeng Qiu, Xuanjing Huang: Extractive Summarization as Text Matching. ACL 2020: 6197-6208'
---
This paper creates a paradigm shift with regard to the way we build neural extractive summarization systems. Instead of following the commonly used framework of extracting sentences individually and modeling the relationship between sentences, we formulate the extractive summarization task as a semantic text matching problem, in which a source document and candidate summaries will be (extracted from the original text) matched in a semantic space. Notably, this paradigm shift to semantic matching framework is well-grounded in our comprehensive analysis of the inherent gap between sentence-level and summary-level extractors based on the property of the dataset. Besides, even instantiating the framework with a simple form of a matching model, we have driven the state-of-the-art extractive result on CNN/DailyMail to a new level (44.41 in ROUGE-1). Experiments on the other five datasets also show the effectiveness of the matching framework. We believe the power of this matching-based summarization framework has not been fully exploited. To encourage more instantiations in the future, we have released our codes, processed dataset, as well as generated summaries in [GitHub](https://github.com/maszhongming/MatchSum).

[Download paper here](http://xuanjing-huang.github.io/files/ext.pdf)
