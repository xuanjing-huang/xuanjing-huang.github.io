---
layout: archive
title: "学术论文"
permalink: /publications/zh/
author_profile: true
lang: zh
---

本页面展示了我的一部分学术论文。如需查看更完整的论文列表，请访问我的[Google Scholar 个人主页](https://scholar.google.com/citations?user=RGsMgZA4H78C)、[Semantic Scholar 个人主页](https://www.semanticscholar.org/author/1790227)、[计算机科学文献数据库](https://dblp.uni-trier.de/pid/05/6735-1.html)或[ACL 论文集](https://aclweb.org/anthology/people/x/xuan-jing-huang/)。

{% if author.googlescholar %}
  您也可以在 <u><a href="{{author.googlescholar}}">我的 Google Scholar 个人主页</a></u> 上找到我的文章。
{% endif %}

{% include base_path %}

{% comment %}On Chinese publications page, show all publications but filter out English translations of Chinese papers{% endcomment %}
{% for post in site.publications reversed %}
  {% comment %}Check if this is an English translation of a Chinese paper{% endcomment %}
  {% assign is_english_translation = false %}
  {% if post.lang == 'en' and post.path contains '-en.md' %}
    {% assign is_english_translation = true %}
  {% endif %}
  
  {% unless is_english_translation %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}