---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
lang: en
---
This page features a selection of my publications. For a more comprehensive list of publications, please refer to my [Google Scholar profile](https://scholar.google.com/citations?user=RGsMgZA4H78C), [Semantic Scholar profile](https://www.semanticscholar.org/author/1790227), [Computer Science Bibliography](https://dblp.uni-trier.de/pid/05/6735-1.html), or [ACL Anthology](https://aclweb.org/anthology/people/x/xuan-jing-huang/).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% comment %}Publications are grouped by pub_category (see _data/pub_categories.yml); newest first within each group. English page shows only lang: en entries.{% endcomment %}
{% assign pubs = site.publications | sort: "date" | reverse %}

<p>
{% for cat in site.data.pub_categories %}<a href="#{{ cat.id }}">{{ cat.en }}</a>{% unless forloop.last %} · {% endunless %}{% endfor %}
</p>

{% for cat in site.data.pub_categories %}
<h2 id="{{ cat.id }}" class="archive__subtitle">{{ cat.en }}</h2>
{% for post in pubs %}
  {% if post.pub_category == cat.id and post.lang == 'en' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
{% endfor %}
