---
layout: archive
title: "Softwares"
permalink: /softwares/
author_profile: true
---

A major part of my research consists of producing packages to solve challenging mathematical problems.
These packages, mainly in the [Julia programming language](https://julialang.org), are available open-source in <a href="https://github.com/tmigot">GitHub @tmigot</a>.

## Solver Stopping in Julia

I am the main developper of [SolverStoppingJulia](https://github.com/SolverStoppingJulia) a github organization whose main package is `Stopping`, a Julia package that offers a framework to implement iterative algorithms and tools to ease the uniformization of stopping criteria in iterative solvers.

* J.-P. Dussault, S. Goyette, T. Migot. [Stopping.jl: A framework to implement iterative algorithms](https://github.com/vepiteski/Stopping.jl), version 0.3.7, 2021.
* T. Migot. [StoppingInterface.jl: Interface between Stopping.jl and other packages](https://github.com/tmigot/StoppingInterface.jl), [doi:10.5281/zenodo.6126665](https://doi.org/10.5281/zenodo.6126665), version 0.1.3, 2022.

With a few lines of codes, one can implement an iterative methods without taking care of the ever debatable stopping criteria.
The motivation behind stopping is to promote reusability of codes ensuring that the user can control, within some algorithmic limits, the stopping criteria of an algorithm.
The documentation of the package contains several examples and tutorials, see the [organization's website](https://solverstoppingjulia.github.io/StoppingTutorials.jl/dev/).

We are now using `Stopping` in a number of packages: [FletcherPenaltyNLPSolver](https://github.com/tmigot/FletcherPenaltyNLPSolver), [OneDmin.jl](https://github.com/vepiteski/OneDmin.jl), [LSDescent](https://github.com/vepiteski/LSDescent), [RandomLinearAlgebraSolvers.jl](https://github.com/tmigot/RandomLinearAlgebraSolvers.jl), and in the [JOVA](https://github.com/JuliaOptimizationVariationalAnalysis) organization.

## JuliaSmoothOptimizers (JSO)

I am an active contributor to the organization [JuliaSmoothOptimizers](https://juliasmoothoptimizers.github.io) an open source organization in the Julia programming language for linear algebra and nonlinear continuous optimization that offers the flexibility, power, and ease of use for studying numerical methods, researching new algorithms, and exploring new ideas.

As a part of my postdoctoral project at IVADO Montreal, I am interested in developing packages to model PDE-constrained optimization problems and implement solvers for such problems.
I am the main developper of two recent packages with official Julia release:
* T. Migot, D. Orban, and A.S. Siquiera. [PDENLPModels.jl: A NLPModel API for optimization problems with PDE-constraints](https://github.com/JuliaSmoothOptimizers/PDENLPModels.jl), [doi:10.5281/zenodo.5056629](https://doi.org/10.5281/zenodo.5056629), version 0.2.3, 2021.
* T. Migot, D. Orban, and A.S. Siquiera. [DCISolver.jl: An optimization solver with dynamic control of infeasibility](https://github.com/JuliaSmoothOptimizers/DCISolver.jl), [doi:10.5281/zenodo.4742979](https://doi.org/10.5281/zenodo.4742979), version 0.2.3, 2021.

Unregistered companion packages for this organization includes:
* T. Migot. [PDEOptimizationProblems: A list of optimization problems in PDENLPModel format](https://github.com/tmigot/PDEOptimizationProblems), 2021.
* T. Migot. [FletcherPenaltyNLPSolver: Fletcher's penalty method for nonlinear optimization models](https://github.com/tmigot/FletcherPenaltyNLPSolver), 2021.

## Julia Optimization and Variational Analysis (JOVA)

I am the founder of [JOVA](https://github.com/JuliaOptimizationVariationalAnalysis) a GitHub open source organization of Julia packages design to model and solve challenging problems such as complentarity problems, (quasi)-variational inequalities, optimization models with degenerate constraints, bilevel optimization models, Nash equilibrium problems, etc. It contains packages to model the problems, state of the art and novel solvers, set of problems.

Currently, the main packages are:
* T. Migot. [ComplementarityModel.jl: Data structure for (linear/nonlinear/mixed)-complementarity problems](https://github.com/JuliaOptimizationVariationalAnalysis/ComplementarityModel.jl), 2021.
* T. Migot. [VariationalInequalitySolver.jl: Set of models and solvers for Variational Inequalities](https://github.com/JuliaOptimizationVariationalAnalysis/VariationalInequalitySolver.jl), 2021.
* T. Migot. [NashGames.jl: Set of models and solvers to compute Nash equilibria](https://github.com/JuliaOptimizationVariationalAnalysis/NashGames.jl), 2021.
* T. Migot. [MPCCSolver.jl: Library of Julia functions to solve MPCC](https://github.com/tmigot/MPCCSolver.jl), 2020.
* T. Migot. [MPCC.jl: Data structures for optimization models with complementarity constraints](https://github.com/tmigot/MPCC.jl), 2020.

The organization created in 2021 is at an early stage and is still recruiting collaborators.
A first step in the creation of this organization is to upload the codes used in my recent research papers.
