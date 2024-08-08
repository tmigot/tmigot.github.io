---
title: 'New Preprint on HAL: Exploring Projected Dynamical Systems in Geochemical Reactions'
date: 2024-07-05
permalink: /posts/2024/07/publis/
tags:
  - publications
  - projected dynamical systems
  - equilibrium problem
  - kinetics reactions
---

This project holds a special place in my heart as it touches on the very applications in geochemistry that first drew me into research.
Equilibrium reactions, particularly in slow processes like the water cycle in aquifers, have always fascinated me.
Moreover, this paper represents an important milestone for one of the authors, Bastien, as it was part of his Ph.D. thesis.
The use of projected dynamical systems, a model I am particularly fond of, adds an additional layer of personal significance to this work.

We added a preprint to the HAL open-access repository, [A projected dynamical system approach to mineral precipitation-dissolution reactions in geochemistry](https://inria.hal.science/hal-04631094). We delve into a novel approach to modeling kinetically-controlled precipitation-dissolution geochemical reactions.
This paper presents a new model that extends the use of ordinary differential equations (ODEs) to accommodate the complexities of non-smoothness induced by full dissolution and the overlapping nature of reactions and minerals.

The model we developed is a specific type of projected dynamical system.
It accounts for the complexities of reactions involving multiple minerals and the participation of a single mineral in several reactions.

![Modified Projected Dynamical System](/images/PDS.png)

Projected dynamical systems are a type of non-smooth differential equation, where the derivative of $x$ follows a dynamic that is projected onto the tangent cone of a convex set (denoted here as $C_0$​).
This approach is commonly used to model ODEs that need to satisfy certain constraints.
In this particular model, we also incorporate an additional proportionality constraint on the derivative of $x$.

We employed a discretization of the system using an explicit scheme, proving the existence of a solution and the convergence of the approximate solution.

![Illustration on two reactions with an aqueous species and two minerals](/images/PDS-example.png)

While the code for this paper is not included in the preprint, it is available upon request. This decision was made to ensure that interested readers can access the tools necessary to replicate and build upon our work.

Projected dynamical systems offer exciting new possibilities for modeling complex geochemical reactions. 
Our work is just one example of how these models can be applied to address long-standing challenges in the field.
I look forward to seeing how this approach evolves and hope it inspires further exploration in both research and practical applications.
