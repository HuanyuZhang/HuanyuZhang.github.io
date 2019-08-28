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
* B.S. in Electronics Engineering, Peking University, 2016
* M.S. in Eletrical and Computer Engineering, Cornell University, 2019
* Ph.D in Eletrical and Computer Engineerin, Cornell University, 2021 (expected)

Work experience
======
* Summer 2019: Research Intern
  * Microsoft Research, Redmond, WA, US
  * Differential Privacy, Statistical Machine Learning, NLP
  * Host: Janardhan Kulkarni

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
