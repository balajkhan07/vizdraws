<!-- README.md is generated from README.Rmd. Please edit that file -->
vizdraws
========

vizdraws allows you to create interactive visualizations of draws from a
prior and posterior distribution.

Example
-------

This is a basic example which shows you how to solve a common problem:

``` r
library(vizdraws)
set.seed(9782)
vizdraws(prior = rnorm(10000, 0, 1), posterior = rnorm(10000, 1.1, 0.5), MME = 0.5, threshold = 0.8)
```

![Posterior distribution](https://home.ignacio.website/Posterior.gif)

Notes
=====

The bell-curve icon was [created by Davo
Sime.](https://thenounproject.com/term/bell-curve/614251/)
