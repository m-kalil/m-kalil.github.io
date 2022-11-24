---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

#2010
[A avaliação da variabilidade das medidas produzidas pelo método radiográfico digital comparadas ao método radiográfico convencional](https://periodicos.uff.br/ijosd/article/view/30466/17700)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
