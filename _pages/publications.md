---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Master thesis
======

[Gaussian process modeling with applications to tumor growth](https://tede.lncc.br//bitstream//tede//339//5//dissertacao_Jo%c3%a3o%20Vitor%20O%20Silva.pdf)

Undergraduate thesis
======

[Generalized eigenvalue problems in linear hydrodynamic stability](https://pantheon.ufrj.br//bitstream//11422//5505//3//Generalized_eigenvalue.pdf)
