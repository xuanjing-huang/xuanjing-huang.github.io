---
layout: archive
title: "Selected Papers"
permalink: /publications/
author_profile: true
---
* Ruize Wang, Duyu Tang, Nan Duan, Zhongyu Wei, Xuanjing Huang, Jianshu Ji, Guihong Cao, Daxin Jiang, Ming Zhou: _K-Adapter: Infusing Knowledge into Pre-Trained Models with Adapters_. ACL/IJCNLP (Findings) 2021: 1405-1418 [[PDF]](https://aclanthology.org/2021.findings-acl.121.pdf)
* Xipeng Qiu, TianXiang Sun, Yige Xu, Yunfan Shao, Ning Dai, Xuanjing Huang, _Pre-trained Models for Natural Language Processing: A Survey_, SCIENCE CHINA Technological Sciences (SCTS) , 2020, Vol. 63(10), pp. 1872–1897 [[PDF]](https://arxiv.org/pdf/2003.08271.pdf)
* Tao Gui, Yicheng Zou, Qi Zhang, Minlong Peng, Jinlan Fu, Zhongyu Wei, Xuanjing Huang: _A Lexicon-Based Graph Neural Network for Chinese NER_. EMNLP/IJCNLP (1) 2019: 1040-1050 [[PDF]](https://aclanthology.org/D19-1096.pdf)
* Pengfei Liu, Xipeng Qiu, Xuanjing Huang: _Adversarial Multi-task Learning for Text Classification_. ACL (1) 2017: 1-10 [[PDF]](https://aclanthology.org/P17-1001.pdf)
* Pengfei Liu, Xipeng Qiu, Xuanjing Huang: _Recurrent Neural Network for Text Classification with Multi-Task Learning_. IJCAI 2016: 2873-2879 [[PDF]](https://arxiv.org/pdf/1605.05101.pdf)

You can also find her publications on her [Google Scholar profile](https://scholar.google.com/citations?user=RGsMgZA4H78C), [Semantic Scholar profile](https://www.semanticscholar.org/author/1790227), [Computer Science Bibliography](https://dblp.org/pid/05/6735), or [ACL Anthology](https://aclweb.org/anthology/people/x/xuan-jing-huang/).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
