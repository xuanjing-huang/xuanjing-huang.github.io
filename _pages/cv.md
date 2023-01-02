---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Computer Science, Fudan University, 1993
* Ph.D in Computer Science, Fudan University, 1998

Work experience
======
* Since 2006: Professor
  * Fudan University

* 2008-2009: Visiting Scholar
  * UMass Amherst

* 2001-2006: Associate Professor
  * Fudan University
  
* 1998-2000: Lecturer
  * Fudan University


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

