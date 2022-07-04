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

Future plans
======

- July, 2022, [JuliaCon 2022](https://juliacon.org/2022/), online.

News
======
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
