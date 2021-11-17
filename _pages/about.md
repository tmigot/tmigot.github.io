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

- May 2022 [Optimization Days](https://symposia.gerad.ca/jopt2022/fr#:~:text=HEC%20Montréal%2C%20Québec%2C%20Canada%2C%2016%20—%2018%20mai%202022), HEC Montreal.

News
======
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
