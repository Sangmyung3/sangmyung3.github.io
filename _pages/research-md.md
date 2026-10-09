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

**[Estimating Heterogeneous Teacher Effects with Grouped Three-Way Interactive Fixed Effects](/files/papers/job_market_paper_Sangmyung_Ha.pdf)**
*(Job Market Paper)*
<div style="margin-left: 2em;">

We develop a grouped three-way interactive fixed-effects model for estimating heterogeneous teacher effects in multidimensional panel data. The model represents unobserved heterogeneity through the low-rank trilinear component \(\sum_{k=1}^{\ell}u_{g(i),k}v_{jk}w_{tk}\), linking observed student types, teachers, and years. Grouping and separability pool information across these dimensions and reduce the number of parameters in the fixed effects relative to a flattened two-way interactive fixed-effects model with unrestricted loadings. We establish aggregate consistency of the global least-squares estimator, derive stochastic expansions and limiting distributions for the slope estimator and aligned factor estimates, and characterize three mode-specific incidental-parameter bias terms. Under the maintained identification and growth conditions, aggregate consistency in balanced panels permits one dimension to remain fixed when the other two diverge. We also develop a consistent information criterion for selecting the number of trilinear components. An application to matched student--teacher achievement data reveals heterogeneity of teacher effects across prior-achievement groups. Under common reference weights, teacher--group matching accounts for approximately \(27\%\) of fitted relative teacher value added variation. A randomized-roster robustness comparison shows a strong descriptive agreement for teacher-level effects.
</div>

---

**A General Factor Model with Common Components Identified by Tensor Structure (with Yoosoon Chang and Joon Y. Park)**
<div style="margin-left: 2em;">

This paper studies the statistical inference in high-dimensional tensor factor models relying on the Canonical Polyadic (CP) decomposition. We show that the factors and their loadings in our models, which are identified up to a trivial permutation of indices and scale changes, can be estimated by a simple alternating least squares (ALS) algorithm. The identified components of our estimators for the factors and their loadings are indeed consistent and asymptotically normal under fairly general conditions. In addition, we develop a test and obtain its asymptotics for determining the number of factors based on the ratio of generalized singular values. As an illustration, we analyze a cross-country panel of key macroeconomic variables across 19 countries over the period from 1979.Q3 to 2023.Q3 to identify global components and investigate heterogeneous effects of the COVID shock at-impact and the subsequent recovery patterns across countries and their linkages with the stringency of their lockdown policies. We find strict lockdown policies initially depressed GDP growth, but they were often associated with a stronger and faster rebound.
</div>

---

**Analysis of Global Yield Curve Using Functional Factor Model with Tensor Structure (with Yoosoon Chang and Joon Y. Park)**
<div style="margin-left: 2em;">

This paper introduces a functional factor model with tensor structure. Our model provides a framework to find and study common features existing in functional fluctuations over time and across cross-sections with their effects having a tensor structure. Such common features, which are required to appear pervasively at all time and across all cross-sections, are defined formally as functional tensor factors in our model. We provide a computational algorithm to extract the functional tensor factors and their loadings within a general framework, as well as a method to estimate the number of them. Their consistency is established as we let the time span \(T\) and the cross-sectional dimension \(N\) increase simultaneously, under a very general set of conditions. We apply our model and methodology to analyze fluctuations of the yield curves of major countries and find one global level factor and three global slope factors from which a curvature factor emerges for some countries.
</div>

---

**[Determining the Structure of Dynamic Factor Models](https://arxiv.org/abs/2606.26142)**
*(Class of 2020 Best Third Year Paper Award)*
<div style="margin-left: 2em;">

We propose two procedures for determining the number of dynamic factors, extending Bai and Ng (2002) and Ahn and Horenstein (2013) to dynamic factor models where lagged factors may directly influence the observed variables. As an intermediate step, we develop a simple and computationally efficient alternating least squares algorithm that directly estimates the dynamic factors, rather than their static representations. By working with these direct estimates, our approach enables joint determination of the number of factors and the filter length. Our approach does not require the exact finite-order VAR specification maintained by Bai and Ng (2007) and Amengual and Watson (2007). We apply our procedures to estimate the number of primitive shocks in a large panel of U.S. macroeconomic time series.
</div>

## Work in Process
**Estimating Large Dimensional Autocovariance Matrices with Application on Network Connectedness of the US State and County Level COVID Cases**

<!-- **Quasi-Maximum Likelihood Estimation of Dynamic Factor Model** -->

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
