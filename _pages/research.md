---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research interests are in causal inference, nonparametric and high-dimensional inference, partial identification, and econometric methods for noisy and rich data settings.

## Research Papers

### Econometrics

[Nested Nonparametric Instrumental Variable Regression](https://doi.org/10.48550/arXiv.2112.14249)
<small>Isaac Meza López and Rahul Singh. Working paper.</small>

[Canonical Correlation Regression with Noisy Data](https://doi.org/10.48550/arXiv.2512.22697)
<small>Isaac Meza López and Rahul Singh. Working paper.</small>

[Residual Balancing for Non-Linear Outcome Models in High Dimensions](https://doi.org/10.48550/arXiv.2511.00324)
<small>Isaac Meza López. Working paper.</small>

### Experimental Design and Applied Microeconomics

[Structured Payment in Pawnshop Borrowing: Mandates vs. Choice](https://isaacmeza.github.io/personal/files/controlled_choice.pdf)
<small>Francis DiTraglia, Craig McIntosh, Isaac Meza López, Enrique Seira Bejarano, and Joyce Sadka. R&amp;R, <em>Review of Economic Studies</em>.</small>

### Earlier Research and Related Projects

[Inference in Synthetic Control Methods Using the Robust Wasserstein Profile Function](https://isaacmeza.github.io/personal/files/scm_inference.pdf)
<small>Isaac Meza López. Research note.</small>

[Genericity of Spaces with the Extended García-Falset Coefficient: \(R(t,X)<1+t\) for Some \(t>0\)](https://isaacmeza.github.io/personal/files/genericity_garcia_falset.pdf)
<small>Isaac Meza López. Research note.</small>

[Bandits and Online Optimization in Infinite Spaces: UMD Spaces are UMD-Learnable](https://isaacmeza.github.io/personal/files/umd_umd.pdf)
<small>Isaac Meza López. Research note.</small>

[The Cameron-Martin Theorem](https://isaacmeza.github.io/personal/files/cameron_martin.pdf)
<small>Technical note.</small>

### Reports and Other Writing

[Did Mexico’s Seguro Popular Universal Health Coverage Programme Really Reduce Formal Jobs?](https://www.wiego.org/publications/did-mexicos-seguro-popular-universal-health-coverage-programme-really-reduce-formal)
<small>Enrique Seira Bejarano, Eduardo González-Pier, Eduardo Alcaraz, and Isaac Meza López. WIEGO Working Paper No. 46.</small>

## Thesis

[Confidence Region via the Robust Wasserstein Profile Function: An Application to Synthetic Control Methods](https://isaacmeza.github.io/personal/files/econ_thesis.pdf)
<small>Bachelor Thesis in Economics. First Place, Research Award ExITAM XXV.</small>

[Geometry of Banach Spaces and Fixed Point Theory](https://isaacmeza.github.io/personal/files/mathematics_thesis_c.pdf)
<small>Bachelor Thesis in Mathematics, in Spanish. Special Mention, Research Award ExITAM XXV.</small>


## Software

[nnpiv](https://nnpiv.readthedocs.io/en/latest/)
<small>Python implementation of nested nonparametric instrumental variables. This package implements methods for estimating nonparametrically nested moment conditions. Related paper: [Meza and Singh](https://arxiv.org/abs/2112.14249).</small>

[tot_tut](https://github.com/isaacmeza/tot_tut)
<small>Stata implementation for estimation of treatment-on-the-treated and treatment-on-the-untreated effects using the design in "Structured Payment in Pawnshop Borrowing: Mandates vs. Choice" by DiTraglia, McIntosh, Meza, Seira, and Sadka.</small>

```stata
net install tot_tut, from(https://raw.githubusercontent.com/isaacmeza/tot_tut/main) replace
```

[fan_park](https://github.com/isaacmeza/fan_park)
<small>Stata implementation of sharp bounds on the distribution of treatment effects of a binary treatment developed in [Fan and Park (2009)](https://doi.org/10.1017/S0266466609990168).</small>

```stata
net install fan_park, from(https://raw.githubusercontent.com/isaacmeza/fan_park/main) replace
```