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

- [25th International Symposium on Mathematical](https://ismp2024.gerad.ca), Montréal, Canada, July 21st-26th, 2024
- [JuMP-dev 2024](https://jump.dev/meetings/jumpdev2024/), Montréal, Canada, July 19th-21th July, 2024

News
======
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
