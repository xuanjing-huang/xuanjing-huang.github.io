---
title: "MouSi: Poly-Visual-Expert Vision-Language Models"
collection: publications
permalink: /publication/mousi
excerpt: 'This paper proposes the use of ensemble experts technique to synergizes the capabilities of individual visual encoders, including those skilled in image-text matching, OCR, image segmentation, etc.'
date: 2024-01-01
venue: 'CoRR abs/2401.17221'
paperurl: 'http://xuanjing-huang.github.io/files/mousi.pdf'
citation: 'Xiaoran Fan, Tao Ji, Changhao Jiang, Shuo Li, Senjie Jin, Sirui Song, Junke Wang, Boyang Hong, Lu Chen, Guodong Zheng, Ming Zhang, Caishuang Huang, Rui Zheng, Zhiheng Xi, Yuhao Zhou, Shihan Dou, Junjie Ye, Hang Yan, Tao Gui, Qi Zhang, Xipeng Qiu, Xuanjing Huang, Zuxuan Wu, Yu-Gang Jiang: MouSi: Poly-Visual-Expert Vision-Language Models. CoRR abs/2401.17221 (2024)'
---
Current large vision-language models (VLMs) often encounter challenges such as insufficient capabilities of a single visual component and excessively long visual tokens. These issues can limit the model’s effectiveness in accurately interpreting complex visual information and over-lengthy contextual information. Addressing these challenges is crucial for enhancing the performance and applicability of VLMs. This paper proposes the use of ensemble experts technique to synergizes the capabilities of individual visual encoders, including those skilled in image-text
matching, OCR, image segmentation, etc. This technique introduces a fusion network to unify the processing of outputs from different visual experts, while bridging the gap between image encoders and pre-trained LLMs. In addition, we explore different positional encoding schemes to alleviate the waste of positional encoding caused by lengthy image feature sequences, effectively addressing the issue of position overflow and length limitations. For instance, in our implementation, this technique significantly reduces the positional occupancy in models like SAM, from a substantial 4096 to a more efficient and manageable 64 or even down to 1. Experimental results demonstrate that VLMs with multiple experts exhibit consistently superior performance over isolated visual encoders and mark a significant performance boost as more experts are integrated.

[Download paper here](http://xuanjing-huang.github.io/files/mousi.pdf)
