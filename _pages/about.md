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

- May, 2023, [JOpt 2023](https://symposia.cirrelt.ca/CORS-JOPT/fr/home), HEC, Montreal, Canada;
- July, 2023, [JuliaCon 2023](https://juliacon.org/2023/), MIT, Boston, USA.

News
======
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
