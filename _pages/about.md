---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

My research focuses on numerical optimization. I am interested in designing algorithms for nonsmooth optimization problems arising in sparse optimization and for non-convex problems, including mathematical programs with complementarity problems, bilevel optimization problems, and generalized Nash equilibrium problems.

I am also very fond of chess and a big fan of Stade Rennais FC!

Future plans
======

News
======
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
