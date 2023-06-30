---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
This page features a selection of my publications. For a more comprehensive list of publications, please refer to my [Google Scholar profile](https://scholar.google.com/citations?user=RGsMgZA4H78C), [Semantic Scholar profile](https://www.semanticscholar.org/author/1790227), [Computer Science Bibliography](https://dblp.dagstuhl.de/pid/05/6735-1.html), or [ACL Anthology](https://aclweb.org/anthology/people/x/xuan-jing-huang/).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
