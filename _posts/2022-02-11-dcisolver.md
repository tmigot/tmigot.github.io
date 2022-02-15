---
title: 'February 2022: DCISolver.jl published in JOSS'
date: 2022-02-11
permalink: /posts/2022/02/publis/
tags:
  - programming
  - Julia
  - PDE
  - optimization
  - data science
  - publications
---
Last December, we submitted a paper to the [Journal of Open Source Software](https://joss.theoj.org) related to the package [`DCISolver.jl`](https://github.com/JuliaSmoothOptimizers/DCISolver.jl) and it is now published!

It is not the first time I submit a paper to a fair open-source journal, and this one is extremely enjoyable. As one can read from the journal's website
```
The Journal of Open Source Software is a developer friendly, open-access journal for research software packages.
```
It is designed to publish papers on packages. The process is entirely on Github, where the editors and reviewers are engaging in a discussion. For instance, following one of the reviewer's suggestions, we added a tutorial with a binder link so you can run it online, [package's documentation](https://juliasmoothoptimizers.github.io/DCISolver.jl/dev/example/). The tutorial shows a comparison with Ipopt on a distributed Poisson control problem with Dirichlet boundary conditions (Spoiler alert: DCI is doing great). Overall, I loved the process and I am already engaged in a review for this journal. The review is clarified by a todo-list of things that needs to be checked.

This package uses a matrix-free feasibility process, but the tangent step still relies on an SQD matrix factorization using [HSL](https://www.hsl.rl.ac.uk/catalogue/) or [LDLFactorizations](https://github.com/JuliaSmoothOptimizers/LDLFactorizations.jl). It is now the obvious next step to make this solver fully matrix-free, see [issue 85](https://github.com/JuliaSmoothOptimizers/DCISolver.jl/issues/85).
