---
layout: archive
title: "简历"
permalink: /cv/zh/
author_profile: true
lang: zh
redirect_from:
  - /resume-zh
---

{% include base_path %}

教育背景
======
* 1993年：复旦大学计算机科学学士
* 1998年：复旦大学计算机科学博士

工作经历
======
* 2006年至今：教授
  * 复旦大学

* 2008-2009年：访问学者
  * 马萨诸塞大学阿默斯特分校

* 2001-2006年：副教授
  * 复旦大学
  
* 1998-2000年：讲师
  * 复旦大学

学术论文
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
学术报告
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
教学
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>