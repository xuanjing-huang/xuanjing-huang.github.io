---
layout: archive
title: "学术论文"
permalink: /publications/zh/
author_profile: true
lang: zh
---

本页面展示了我的一部分学术论文。如需查看更完整的论文列表，请访问我的[Google Scholar 个人主页](https://scholar.google.com/citations?user=RGsMgZA4H78C)、[Semantic Scholar 个人主页](https://www.semanticscholar.org/author/1790227)、[计算机科学文献数据库](https://dblp.dagstuhl.de/pid/05/6735-1.html)或[ACL 论文集](https://aclweb.org/anthology/people/x/xuan-jing-huang/)。

{% if author.googlescholar %}
  您也可以在 <u><a href="{{author.googlescholar}}">我的 Google Scholar 个人主页</a></u> 上找到我的文章。
{% endif %}

{% include base_path %}

{% comment %} Filter Chinese publications only {% endcomment %}
{% assign chinese_publications = site.publications | where: "lang", "zh" %}
{% for post in chinese_publications reversed %}
  {% include archive-single.html %}
{% endfor %}