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

- [25th International Symposium on Mathematical](https://ismp2024.gerad.ca), Montréal, Canada, July 21st-26th, 2024
- [JuMP-dev 2024](https://jump.dev/meetings/jumpdev2024/), Montréal, Canada, July 19th-21th July, 2024

News
======
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
