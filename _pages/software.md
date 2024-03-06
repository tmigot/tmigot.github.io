---
layout: archive
title: "Softwares"
permalink: /softwares/
author_profile: true
---

Part of my research consists of producing packages to solve challenging mathematical problems.
These packages, mainly in the [Julia programming language](https://julialang.org) but also C++ or Python, are available open-source in <a href="https://github.com/tmigot">GitHub @tmigot</a>.

## JuliaSmoothOptimizers (JSO)

I am an active contributor to the organization [JuliaSmoothOptimizers](https://jso.dev) an open-source organization in the Julia programming language for linear algebra and nonlinear continuous optimization that offers the flexibility, power, and ease of use for studying numerical methods, researching new algorithms, and exploring new ideas. Apart from my contributions to the 76 (!) Julia packages of the organization, I also write tutorials and news on the organization's website.

I usually present the progress of the organization at the JuliaCon or JuMP-dev conferences.

If you are not familiar with JSO, the following packages are good starting points:
* Migot, T., Montoison, A., Orban, D., Soares Siqueira, A., & contributors (2023). ADNLPModels.jl: Automatic Differentiation models implementing the NLPModels API (Version 0.7.0) [Computer software]. [github.com/JuliaSmoothOptimizers/ADNLPModels.jl](https://github.com/JuliaSmoothOptimizers/ADNLPModels.jl), [doi:10.5281/zenodo.4605982](https://doi.org/10.5281/zenodo.4605982);
* Migot, T., Orban, D., Soares Siqueira, A., & contributors. (2023). JSOSuite.jl: One stop solutions for all things optimization (Version 0.1.0) [Computer software]. [github.com/JuliaSmoothOptimizers/JSOSuite.jl](https://github.com/JuliaSmoothOptimizers/JSOSuite.jl), [10.5281/zenodo.8246389](https://doi.org/10.5281/zenodo.8246389);
* Migot, T., Orban, D., Soares Siqueira, A., & contributors. (2023). OptimizationProblems.jl: A collection of optimization problems in Julia (Version 0.7.3) [Computer software]. [https://github.com/JuliaSmoothOptimizers/OptimizationProblems.jl](github.com/JuliaSmoothOptimizers/OptimizationProblems.jl), [doi:10.5281/zenodo.3672094](https://doi.org/10.5281/zenodo.3672094).

As a part of my research project at IVADO/Polytechnique Montreal, I was interested in developing packages to model PDE-constrained optimization problems and implement solvers for such problems.

* Migot, T., Orban, D., Soares Siqueira, A., & contributors (2022). [PDENLPModels.jl: A NLPModel API for optimization problems with PDE-constraints](https://github.com/JuliaSmoothOptimizers/PDENLPModels.jl), The Journal of Open Source Software, 7(80), 4736. [doi:10.21105/joss.04736](https://doi.org/10.21105/joss.04736);
* Migot, T., Orban, D., Soares Siqueira, A., & contributors (2022). [DCISolver.jl: A Julia Solver for Nonlinear Optimization using Dynamic Control of Infeasibility](https://github.com/JuliaSmoothOptimizers/DCISolver.jl). The Journal of Open Source Software, 70(7), 3991, [doi:10.21105/joss.03991](https://doi.org/10.21105/joss.03991);
* Migot, T., Orban, D., Soares Siqueira, A., & contributors (2023). FletcherPenaltySolver.jl: Fletcher's penalty method for nonlinear optimization models (Version 0.2.4) [Computer software]. [github.com/JuliaSmoothOptimizers/FletcherPenaltySolver.jl](https://github.com/JuliaSmoothOptimizers/FletcherPenaltySolver.jl), [doi:10.5281/zenodo.7153564](https://doi.org/10.5281/zenodo.7153564);
* Dussault, J.-P., Goyette, S., Migot, T., Orban, D., & contributors (2023). AdaptiveRegularization.jl: A unified efficient implementation of trust-region type algorithms for unconstrained optimization (Version 0.1.0) [Computer software]. [github.com/JuliaSmoothOptimizers/AdaptiveRegularization.jl](https://github.com/JuliaSmoothOptimizers/AdaptiveRegularization.jl), [doi:10.5281/zenodo.10434673](https://doi.org/10.5281/zenodo.10434673);
* Migot, T., & contributors (2024). PDEOptimizationProblems: A list of optimization problems in PDENLPModel format (Version 0.1.0) [Computer software]. [github.com/tmigot/PDEOptimizationProblems](https://github.com/tmigot/PDEOptimizationProblems).

The organization also contains more very interesting research-level and efficient solvers such as
* Migot, T., Orban, D., Soares Siqueira, A., & contributors. (2023). JSOSolvers.jl: JuliaSmoothOptimizers optimization solvers (Version 0.11.0) [Computer software]. [github.com/JuliaSmoothOptimizers/JSOSolvers.jl](https://github.com/JuliaSmoothOptimizers/JSOSolvers.jl), [doi:10.5281/zenodo.3991143](https://doi.org/10.5281/zenodo.3991143);
* Antunes dos Santos, E., Migot, T., Orban, D., Soares Siqueira, A., & contributors. (2023). Percival.jl: an augmented Lagrangian method (Version 0.7.0) [Computer software]. [github.com/JuliaSmoothOptimizers/Percival.jl](https://github.com/JuliaSmoothOptimizers/Percival.jl), [doi:10.5281/zenodo.3969045](https://doi.org/10.5281/zenodo.3969045);
* Migot, T., Orban, D., Soares Siqueira, A., & contributors. (2023). CaNNOLeS.jl: Constrained and NoNlinear Optimizer of Least Squares (Version 0.7.0) [Computer software]. [github.com/JuliaSmoothOptimizers/CaNNOLeS.jl](https://github.com/JuliaSmoothOptimizers/CaNNOLeS.jl), [doi:10.5281/zenodo.4154524](https://doi.org/10.5281/zenodo.4154524).

## Solver Stopping in Julia

I am the main developer of [SolverStoppingJulia](https://github.com/SolverStoppingJulia) a Github organization whose main package is `Stopping`, a Julia package that offers a framework to implement iterative algorithms and tools to ease the uniformization of stopping criteria in iterative solvers.

* J.-P. Dussault, S. Goyette, T. Migot. [Stopping.jl: A framework to implement iterative algorithms](https://github.com/SolverStoppingJulia/Stopping.jl), version 0.6.0 2022.
* T. Migot. [StoppingInterface.jl: Interface between Stopping.jl and other packages](https://github.com/SolverStoppingJulia/StoppingInterface.jl), [doi:10.5281/zenodo.6126665](https://doi.org/10.5281/zenodo.6126665), version 0.5.1, 2022.

With a few lines of code, one can implement an iterative method without taking care of the ever-debatable stopping criteria.
The motivation behind stopping is to promote the reusability of codes ensuring that the user can control, within some algorithmic limits, the stopping criteria of an algorithm.
The documentation of the package contains several examples and tutorials, see the [organization's website](https://solverstoppingjulia.github.io/StoppingTutorials.jl/dev/).

`Stopping` is used in several packages: [AdaptiveRegularization.jl](https://github.com/JuliaSmoothOptimizers/AdaptiveRegularization.jl), [FletcherPenaltySolver](https://github.com/JuliaSmoothOptimizers/FletcherPenaltySolver.jl), [OneDmin.jl](https://github.com/vepiteski/OneDmin.jl), [LSDescent](https://github.com/vepiteski/LSDescent), [RandomLinearAlgebraSolvers.jl](https://github.com/tmigot/RandomLinearAlgebraSolvers.jl), and more to come.

## Julia Optimization and Variational Analysis (JOVA)

I am the founder of [JOVA](https://github.com/JuliaOptimizationVariationalAnalysis) a GitHub open-source organization of Julia packages designed to model and solve challenging problems such as complementarity problems, (quasi)-variational inequalities, optimization models with degenerate constraints, bilevel optimization models, Nash equilibrium problems, etc. It contains packages to model the problems, state-of-the-art and novel solvers, set of problems.

The organization created in 2021 is at an early stage and is still recruiting collaborators.
A first step in the creation of this organization is the upload of the codes used in my recent research papers.
