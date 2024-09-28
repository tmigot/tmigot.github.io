---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Computational scientist specializing in solving challenging mathematical problems and their practical applications, my primary expertise lies in numerical optimization.
I specialize in addressing nonconvex problems, including mathematical programs with complementarity problems, bilevel optimization, and generalized Nash games, and nonsmooth optimization problems arising in sparse optimization.
I use optimal control and nonsmooth dynamical systems in diverse applications such as game theory and geochemistry.
 An important aspect of my research is to make algorithms accessible and competitive for large-scale problems encountered in machine learning, earth sciences, and life sciences.

I am always open to new collaborations and opportunities, so feel free to reach out!

Future plans
======

- More to come soon.

News
======
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
