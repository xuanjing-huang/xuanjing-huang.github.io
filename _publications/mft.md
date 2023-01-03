---
title: "A Multi-Format Transfer Learning Model for Event Argument Extraction via Variational Information Bottleneck"
collection: publications
permalink: /publication/mft
excerpt: 'In this paper, we propose a multi-format transfer learning model with variational information bottleneck for EAE in new datasets.'
date: 2022-10-12
venue: 'COLING'
paperurl: 'http://xuanjing-huang.github.io/files/mft.pdf'
citation: 'XJie Zhou, Qi Zhang, Qin Chen, Liang He, Xuanjing Huang: A Multi-Format Transfer Learning Model for Event Argument Extraction via Variational Information Bottleneck. COLING 2022: 1990-2000'
---
Event argument extraction (EAE) aims to extract arguments with given roles from texts, which have been widely studied in natural language processing. Most previous works have achieved good performance in specific EAE datasets with dedicated neural architectures. Whereas, these architectures are usually difficult to adapt to new datasets/scenarios with various annotation schemas or formats. Furthermore, they rely on large-scale labeled data for training, which is unavailable due to the high labelling cost in most cases. In this paper, we propose a multi-format transfer learning model with variational information bottleneck, which makes use of the information especially the common knowledge in existing datasets for EAE in new datasets. Specifically, we introduce a shared-specific prompt framework to learn both format-shared and format-specific knowledge from datasets with different formats. In order to further absorb the common knowledge for EAE and eliminate the irrelevant noise, we integrate variational information bottleneck into our architecture to refine the shared representation. We conduct extensive experiments on three benchmark datasets, and obtain new state-of-the-art performance on EAE.

[Download paper here](http://xuanjing-huang.github.io/files/mft.pdf)
