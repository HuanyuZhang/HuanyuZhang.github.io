---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

All the following papers have alphabetical author order, which is a custom in theoretical computer science.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-pub.html %}
{% endfor %}
