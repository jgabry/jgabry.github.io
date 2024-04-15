---
title: Jonah Sol Gabry
layout: default
---

## Software and papers

**Jump to:**      
* [Stan](#stan)
* [R packages](#r-packages)
* [Papers](#papers)
* [Tutorials and educational materials](#tutorials-and-educational-materials)

<hr>

## Stan

**Stan** is a statistical modeling language along with inference algorithms for full
Bayesian inference, approximate Bayesian inference, and penalized maximum likelihood
estimation. Stan is implemented in C++ but we provide interfaces for the
command line, R and Python (and more).
<br>

* [Stan website](https://mc-stan.org)
* [The Stan Forums](https://discourse.mc-stan.org) (on Discourse)
* [stan-dev GitHub organization](https://github.com/stan-dev)
* [Stan Development Team](https://mc-stan.org/team/)


## R packages

**rstan**

[![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version/rstan)](https://cran.r-project.org/package=rstan)[![RStudio_CRAN_mirror_downloads_badge](https://cranlogs.r-pkg.org/badges/rstan?color=blue)](https://cran.r-project.org/web/packages/rstan)

The **rstan** package is the [R](https://www.r-project.org) interface to Stan.
<br>
[**website**](https://mc-stan.org/rstan) |
[**CRAN**](https://cran.r-project.org/package=rstan) |
[**source code on GitHub**](https://github.com/stan-dev/rstan)

<br>

**rstanarm**

[![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version/rstanarm)](https://cran.r-project.org/package=rstanarm)
[![RStudio_CRAN_mirror_downloads_badge](https://cranlogs.r-pkg.org/badges/rstanarm?color=blue)](https://cran.r-project.org/web/packages/rstanarm)

The **rstanarm** package is for Bayesian applied regression modeling (ARM) via Stan.
It is an appendage to the **rstan** package that enables some of the
most common applied regression models to be estimated using Markov Chain
Monte Carlo, variational approximations to the posterior distribution, or
optimization. The **rstanarm** package allows these models to be
 specified using the customary R modeling syntax (e.g., like that of
`glm` with a `formula` and a `data.frame`).
<br>
[**website**](https://mc-stan.org/rstanarm) |
[**CRAN**](https://cran.r-project.org/package=rstanarm) |
[**source code on GitHub**](https://github.com/stan-dev/rstanarm)

<br>

**shinystan**

[![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version/shinystan)](https://cran.r-project.org/package=shinystan)
[![RStudio_CRAN_mirror_downloads_badge](https://cranlogs.r-pkg.org/badges/shinystan?color=blue)](https://cran.r-project.org/web/packages/shinystan)

The **shinystan** R package provides a graphical user interface providing
interactive visual and numerical summaries of model parameters and convergence
diagnostics for Bayesian models estimated using MCMC.
<br>
[**website**](https://mc-stan.org/shinystan) |
[**CRAN**](https://cran.r-project.org/package=shinystan) |
[**source code on GitHub**](https://github.com/stan-dev/shinystan)

<br>

**bayesplot**

[![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version/bayesplot)](https://cran.r-project.org/package=bayesplot)[![RStudio_CRAN_mirror_downloads_badge](https://cranlogs.r-pkg.org/badges/bayesplot?color=blue)](https://cran.r-project.org/web/packages/bayesplot)

The **bayesplot** R package provides a library of plotting functions for use
after fitting Bayesian models (typically with MCMC).
<br>
[**website**](https://mc-stan.org/bayesplot) |
[**CRAN**](https://cran.r-project.org/package=bayesplot) |
[**source code on GitHub**](https://github.com/stan-dev/bayesplot)

A paper about **bayesplot** and visualization in the Bayesian workflow more generally:

* Jonah Gabry, Daniel Simpson, Aki Vehtari, Michael Betancourt, and Andrew Gelman. (2017). Visualization in Bayesian workflow.
[arXiv preprint arxiv:1709.01449](https://arxiv.org/abs/1709.01449)

<br>

**loo**

[![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version/loo)](https://cran.r-project.org/package=loo)
[![RStudio_CRAN_mirror_downloads_badge](https://cranlogs.r-pkg.org/badges/loo?color=blue)](https://cran.r-project.org/web/packages/loo)

The **loo** R package is for efficient approximate leave-one-out cross-validation for Bayesian models.
<br>
[**website**](https://mc-stan.org/loo) |
[**CRAN**](https://cran.r-project.org/package=loo) |
[**source code on GitHub**](https://github.com/stan-dev/loo)

The package implements the methods described in these papers with Aki and Andrew:

* Aki Vehtari, Andrew Gelman, and Jonah Gabry. (2017). Practical Bayesian model evaluation using leave-one-out cross-validation and WAIC. _Statistics and Computing_. 27(5), pp 1413-1432. [(link to published version)](https://link.springer.com/article/10.1007/s11222-016-9696-4)
 | [arXiv preprint arxiv:1507.04544](arxiv.org/abs/1507.04544)

* Aki Vehtari, Andrew Gelman, and Jonah Gabry. (2016). Pareto smoothed importance sampling.
[arXiv preprint arxiv:1507.02646](https://arxiv.org/abs/1507.02646)

<br>

**rstantools**

[![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version/rstantools)](https://cran.r-project.org/package=rstantools)[![RStudio_CRAN_mirror_downloads_badge](https://cranlogs.r-pkg.org/badges/rstantools?color=blue)](https://cran.r-project.org/web/packages/rstantools)

The **rstantools** R package provides tools for developing R packages interfacing with Stan.
<br>
[**website**](https://mc-stan.org/rstantools) |
[**CRAN**](https://cran.r-project.org/package=rstantools) |
[**source code on GitHub**](https://github.com/stan-dev/rstantools)

<br>

**posterior**

[![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version/posterior)](https://cran.r-project.org/package=posterior)[![RStudio_CRAN_mirror_downloads_badge](https://cranlogs.r-pkg.org/badges/posterior?color=blue)](https://cran.r-project.org/web/packages/posterior)

The **posterior** R package provides efficient conversion between many different useful formats 
of draws (samples) from posterior or prior distributions, consistent methods for operations commonly 
performed on draws, various summaries of draws in convenient formats, and lightweight implementations 
of state of the art posterior inference diagnostics.
<br>
[**website**](https://mc-stan.org/posterior) |
[**CRAN**](https://cran.r-project.org/package=posterior) |
[**source code on GitHub**](https://github.com/stan-dev/posterior)

<br>

**cmdstanr**

<!--
[![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version/cmdstanr)](https://cran.r-project.org/package=cmdstanr)[![RStudio_CRAN_mirror_downloads_badge](https://cranlogs.r-pkg.org/badges/cmdstanr?color=blue)](https://cran.r-project.org/web/packages/cmdstanr)
-->

The **cmdstanr** R package provides an R interface to CmdStan.
<br>
<!-- [**website**](https://mc-stan.org/cmdstanr) |
[**CRAN**](https://cran.r-project.org/package=cmdstanr) |
[**source code on GitHub**](https://github.com/stan-dev/cmdstanr) -->
[**website**](https://mc-stan.org/cmdstanr) | [**source code on GitHub**](https://github.com/stan-dev/cmdstanr)

<br>



## Papers

* [[2024] Pareto Smoothed Importance Sampling](https://arxiv.org/pdf/1507.02646). *Journal of Machine Learning Research* (Aki Vehtari, Daniel Simpson, Andrew Gelman, Yuling Yao, Jonah Gabry)
* [[2022] Fast methods for posterior inference of two-group normal-normal models](http://www.stat.columbia.edu/~gelman/research/published/two_group_fastnono.pdf). _Bayesian Analysis_ (Philip Greengard, Jeremy Hoskins, Charles C. Margossian, Jonah Gabry, Andrew Gelman, Aki Vehtari)
* [[2020] Efficient leave-one-out cross-validation for Bayesian non-factorized normal and Student-t models](https://arxiv.org/pdf/1810.10559.pdf). _Computational Statistics_ (Paul Bürkner, Jonah Gabry, Aki Vehtari)
* [[2020] Approximate leave-future-out cross-validation for Bayesian time series models](https://arxiv.org/pdf/1902.06281.pdf). _Journal of Statistical Computation and Simulation_ (Paul Bürkner, Jonah Gabry, Aki Vehtari)
* [[2020] Bayesian hierarchical weighting adjustment and survey inference](https://arxiv.org/pdf/1707.08220). _Survey Methodology_ (Yajuan Si, Rob Trangucci, Jonah Gabry, Andrew Gelman)
* [[2019] Visualization in Bayesian workflow](https://doi.org/10.1111/rssa.12378) (with discussion). _Journal of the Royal Statistical Society A_. (Jonah Gabry, Daniel Simpson, Aki Vehtari, Michael Betancourt, Andrew Gelman)
* [[2018] R-squared for Bayesian regression models](http://www.stat.columbia.edu/~gelman/research/published/bayes_R2_v3.pdf). _The American Statistician_. (Andrew Gelman, Ben Goodrich, Jonah Gabry, Aki Vehtari) 
* [[2018] User-friendly Bayesian regression modeling](https://www.tqmp.org/RegularArticles/vol14-2/p099/p099.pdf). _The Quantitative Methods for Psychology_. (Chelsea Muth, Zita Oravecz, Jonah Gabry)
* [[2018] Bayesian hierarchical models for predicting individual performance in soccer](https://www.degruyter.com/view/j/jqas.2018.14.issue-3/jqas-2017-0066/jqas-2017-0066.xml). _Journal of Quantitative Analysis in Sports_. (Leonardo Egidi and Jonah Gabry)
* [[2017] Practical Bayesian model evaluation using leave-one-out cross-validation and WAIC](https://arxiv.org/pdf/1507.04544). _Statistics and Computing_. (Aki Vehtari, Andrew Gelman, Jonah Gabry) 
* [[2017] Antiemetic prophylaxis as a marker of health care disparities in the National Anesthesia Clinical Outcomes Registry](https://www.ncbi.nlm.nih.gov/pubmed/29116968). _Anesthesia & Analgesia_. (Michael Andreae, Jonah Gabry, Ben Goodrich, Robert White, Charles Hall)
* [[2017] A pragmatic trial to improve adherence with scheduled appointments in an inner-city pain clinic by human phone calls in the patient’s preferred language](https://www.ncbi.nlm.nih.gov/pubmed/28841451). _Journal of Clinical Anesthesia_. (Michael Andreae, Singh Nair, Jonah Gabry, Ben Goodrich, Charles Hall, Naum Shaparin)


Preprints: 

* [Baysian workflow](https://arxiv.org/abs/2011.01808) (Andrew Gelman, Aki Vehtari, Daniel Simpson, Charles C. Margossian, Bob Carpenter, Yuling Yao, Lauren Kennedy, Jonah Gabry, Paul-Christian Bürkner, Martin Modrák)
* [Using multilevel regression and poststratification to estimate dynamic public opinion](http://www.stat.columbia.edu/~gelman/research/unpublished/MRT(1).pdf). (Andrew Gelman, Jeffrey Lax, Justin Phillips, Jonah Gabry, Robert Trangucci) 


## Tutorials and educational materials

A selection of tutorial vignettes on practical topics in Bayesian data analysis.

#### Visualization

* [Visual MCMC diagnostics](https://mc-stan.org/bayesplot/articles/visual-mcmc-diagnostics.html)
* [Plotting MCMC draws](https://mc-stan.org/bayesplot/articles/plotting-mcmc-draws.html)
* [Graphical posterior predictive checks](https://mc-stan.org/bayesplot/articles/graphical-ppcs.html)

#### Bayesian regression modeling with **rstanarm**

* [GLMs for Binary/Binomial Data](https://mc-stan.org/rstanarm/articles/binomial.html)
* [GLMs for Continuous Data](https://mc-stan.org/rstanarm/articles/continuous.html)
* [GLMs for Count Data](https://mc-stan.org/rstanarm/articles/count.html)
* [Generalized (Non-)Linear Models with Group-Specific Terms](https://mc-stan.org/rstanarm/articles/glmer.html)
* [Bayesian ANOVA Models](https://mc-stan.org/rstanarm/articles/aov.html)
* [Regularized Linear Models](https://mc-stan.org/rstanarm/articles/lm.html)
* [Ordinal Regression Models](https://mc-stan.org/rstanarm/articles/polr.html)
* [Hierarchical Partial Pooling for Repeated Binary Trials](https://mc-stan.org/rstanarm/articles/pooling.html)
* [Modeling Rates/Proportions using Beta Regression](https://mc-stan.org/rstanarm/articles/betareg.html)
* [Multilevel regression and poststratification](https://mc-stan.org/rstanarm/articles/mrp.html)

#### Predictive performance and model comparison

* [Using the loo package (version >= 2.0.0)](https://mc-stan.org/loo/articles/loo2-example.html)
* [Bayesian Stacking and Pseudo-BMA weights](https://mc-stan.org/loo/articles/loo2-weights.html)
* [Writing Stan programs for use with the loo package](https://mc-stan.org/loo/articles/loo2-with-rstan.html)
* [Leave-one-out cross-validation for non-factorizable models](https://mc-stan.org/loo/articles/loo2-non-factorizable.html)
* [Approximate leave-future-out cross-validation for time series models](https://mc-stan.org/loo/articles/loo2-lfo.html)
* [Using Leave-one-out cross-validation for large data](https://mc-stan.org/loo/articles/loo2-large-data.html)

#### Developing R packages with pre-compiled Stan programs

* [Step by step guide for creating a package that depends on RStan](https://mc-stan.org/rstantools/articles/minimal-rstan-package.html)
