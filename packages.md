---
site:
  hide_toc: true
  hide_footer_links: true
---

# Packages

<!--
::::{grid} 1 1 2 3

:::{card}
:header: Package 1
...
:::

:::{card}
:header: Package 2
...
:::

:::{card}
:header: Package 3
...
:::
::::

# Pilot Projects
-->

As part of our NSF-funded initiative, we are working with two pilot projects that highlight different aspects of the statistical Python ecosystem:

- **[YAGLM](https://github.com/yaglm/yaglm)**: A Python package for generalized linear models (GLM), offering modern statistical methodology with various loss functions, regularizers, and solvers.
  GLMs are a flexible and powerful generalization of ordinary linear regression and cover many statistical models widely used in applications.
  Beyond the basic LASSO/ridge penalties, the package supports structured penalties such as the nuclear norm as well as the group, exclusive, fused, and generalized lasso and non-convex penalties.
  It comes with a variety of tuning parameter selection methods including: cross-validation, information criteria that have favorable model selection properties, and degrees of freedom estimators.
- **[ISLP](https://github.com/intro-stat-learning/ISLP)**: A companion Python package for the textbook "An Introduction to Statistical Learning with Applications in Python," closely following the examples in its hugely successful `R` version.
  Besides just providing labs, it provides Pythonic design matrix building, a simple implementation of Bayesian Additive Regression Trees and object oriented stepwise model selection.
