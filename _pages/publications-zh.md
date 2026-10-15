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

{% comment %}Publications are grouped by pub_category (see _data/pub_categories.yml); newest first within each group. Chinese page shows all entries except English translations (-en.md) of Chinese papers.{% endcomment %}
{% assign pubs = site.publications | sort: "date" | reverse %}

<p>
{% for cat in site.data.pub_categories %}<a href="#{{ cat.id }}">{{ cat.zh }}</a>{% unless forloop.last %} · {% endunless %}{% endfor %}
</p>

{% for cat in site.data.pub_categories %}
<h2 id="{{ cat.id }}" class="archive__subtitle">{{ cat.zh }}</h2>
{% for post in pubs %}
  {% if post.pub_category == cat.id %}
    {% assign is_english_translation = false %}
    {% if post.lang == 'en' and post.path contains '-en.md' %}
      {% assign is_english_translation = true %}
    {% endif %}
    {% unless is_english_translation %}
      {% include archive-single.html %}
    {% endunless %}
  {% endif %}
{% endfor %}
{% endfor %}