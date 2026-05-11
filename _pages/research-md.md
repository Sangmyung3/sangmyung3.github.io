---
layout: archive
title: "Research"
permalink: /research-md/
author_profile: true
# redirect_from:
#   - /resume
---

{% include base_path %}

## Working Papers
**[Determining the Structure of Dynamic Factor Models](../files/papers/DFM_test.pdf)**
<div style="margin-left: 2em;">

We propose a simple and computationally efficient alternating least squares (ALS) algorithm for estimating dynamic factor models with finite filter length. We demonstrate that the factors and factor loadings are consistent up to an invertible matrix whose dimension equals the number of dynamic factors. Building on this result, we introduce two procedures for selecting the number of dynamic factors and the filter length. We illustrate the practical usefulness of the proposed framework through two empirical applications. First, we estimate impulse responses to monetary policy shocks identified using a large-dimensional system. Second, we construct directional connectedness measures for U.S. state-level and county-level COVID-19 positive cases.
</div>

---

**Tensor Factor Model with CP Structure (with Yoosoon Chang and Joon Park)**
<div style="margin-left: 2em;">

This paper studies the statistical inference in high-dimensional tensor factor models relying on the Canonical Polyadic (CP) decomposition. We show that the factors and their loadings in our models, which are identified up to a trivial permutation of indices and scale changes, can be estimated by a simple alternating least squares (ALS) algorithm. The identified components of our estimators for the factors and their loadings are indeed consistent and asymptotically normal under fairly general conditions. In addition, we develop a test and obtain its asymptotics for determining the number of factors based on the ratio of generalized singular values.
</div>

---

**Analysis of Global Yield Curve Using Functional Factor Model with Tensor Structure (with Yoosoon Chang and Joon Park)**
<div style="margin-left: 2em;">

This paper introduces a functional factor model with tensor structure. Our model provides a framework to find and study common features existing in functional fluctuations over time and across cross-sections with their effects having a tensor structure. Such common features, which are required to appear pervasively at all time and across all cross-sections, are defined formally as functional tensor factors in our model. We provide a computational algorithm to extract the functional tensor factors and their loadings within a general framework, as well as a method to estimate the number of them. Their consistency is established as we let the time span T and the cross-sectional dimension N increase simultaneously, under a very general set of conditions. We apply our model and methodology to analyze fluctuations of the yield curves of major countries and find one global level factor and three global slope factors from which a curvature factor emerges for some countries.
</div>


## Work in Process
**Quasi-Maximum Likelihood Estimation of Dynamic Factor Model**

<!-- Three way panel data model with interactive fixed effects (Testing the interactive structure becomes important here, include funtion to scalar panel regression as an extension) -->
<!-- Tensor Factor Model with Mixed Structure (Include both bi-linear and tri-linear factors, extension to functional data) 
y_{it}(r) = \beta_t'f_i(r) + \varepsilon_{it}(r)
y_{it}(r) = \beta_t(r)'f_i + \varepsilon_{it}(r)
y_{it}(r) = \beta_{it}'f(r) + \varepsilon_{it}(r)
y_{it}(r) = (\beta_{i}'\ast f')\alpha(r) + \varepsilon_{it}(r)
-->

<!-- Panel data model with nonlinear (nonparametric) interactive fixed effects -->
<!-- Panel data model with regime switching (grouped) interactive fixed effects -->
<!-- Mixed Functional Factor Model with Homogenous Basis -->
<!-- panel data model with interactive dynamic fixed effects -->