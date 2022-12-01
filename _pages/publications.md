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

<br>

Master thesis
======

### Gaussian process modeling with applications to tumor growth 
*Laboratório Nacional de Computação Científica, 2021*
<br><br>
This work proposes the use of a data-driven Gaussian process surrogate model in order to alleaviate the computational burden of performing Approximate Bayesian Computation of complex tumor growth model.

[Link](http://jvitordeoliveira96.github.io/files/dissertacao_jvos_.pdf)

Undergraduate thesis
======

### Generalized eigenvalue problems in linear hydrodynamic stability 
*Universidade Federal do Rio de Janeiro, 2018*<br>
*Prêmio Beatriz Neves - 2nd place (undergraduate thesis national award)*
<br><br>
This work compares distinct methods of solving generalized eigenvalue problems (GEVPs) associated with linear hydrodynamic stability problems. 

[Link](http://jvitordeoliveira96.github.io/files/tcc_generalized_eigen.pdf)
