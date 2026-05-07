---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research interests are in causal inference, nonparametric and high-dimensional inference, partial identification, and econometric methods for noisy and rich data settings.

## Research Papers

### Econometrics

- <span style="font-size: 0.9em;">[Nested Nonparametric Instrumental Variable Regression](https://doi.org/10.48550/arXiv.2112.14249)</span>
<small>Isaac Meza and Rahul Singh. Working paper.</small>

- <span style="font-size: 0.9em;">[Canonical Correlation Regression with Noisy Data](https://doi.org/10.48550/arXiv.2512.22697)</span>
<small>Isaac Meza and Rahul Singh. Working paper.</small>

- <span style="font-size: 0.9em;">[Residual Balancing for Non-Linear Outcome Models in High Dimensions](https://doi.org/10.48550/arXiv.2511.00324)</span>
<small>Isaac Meza. Working paper.</small>

### Experimental Design and Applied Microeconomics

- <span style="font-size: 0.9em;">[Structured Payment in Pawnshop Borrowing: Mandates vs. Choice](https://isaacmeza.github.io/personal/files/controlled_choice.pdf)</span>
<small>Francis DiTraglia, Craig McIntosh, Isaac Meza, Enrique Seira Bejarano, and Joyce Sadka. R&amp;R, <em>Review of Economic Studies</em>.</small>

### Earlier Research and Related Projects

- <span style="font-size: 0.9em;">[Inference in Synthetic Control Methods Using the Robust Wasserstein Profile Function](https://isaacmeza.github.io/personal/files/scm_inference.pdf)</span>
<small>Isaac Meza. Research note.</small>

- <span style="font-size: 0.9em;">[Genericity of Spaces with the Extended García-Falset Coefficient: \(R(t,X)<1+t\) for Some \(t>0\)](https://isaacmeza.github.io/personal/files/genericity_garcia_falset.pdf)</span>
<small>Isaac Meza. Research note.</small>

- <span style="font-size: 0.9em;">[Bandits and Online Optimization in Infinite Spaces: UMD Spaces are UMD-Learnable](https://isaacmeza.github.io/personal/files/umd_umd.pdf)</span>
<small>Isaac Meza. Research note.</small>

- <span style="font-size: 0.9em;">[The Cameron-Martin Theorem](https://isaacmeza.github.io/personal/files/cameron_martin.pdf)</span>
<small>Isaac Meza. Technical note.</small>

### Reports and Other Writing

- <span style="font-size: 0.9em;">[Did Mexico’s Seguro Popular Universal Health Coverage Programme Really Reduce Formal Jobs?](https://www.wiego.org/publications/did-mexicos-seguro-popular-universal-health-coverage-programme-really-reduce-formal)</span>
<small>Enrique Seira Bejarano, Eduardo González-Pier, Eduardo Alcaraz, and Isaac Meza. WIEGO Working Paper No. 46.</small>

## Thesis

- <span style="font-size: 0.9em;">[Confidence Region via the Robust Wasserstein Profile Function: An Application to Synthetic Control Methods](https://isaacmeza.github.io/personal/files/econ_thesis.pdf)</span>
<small>Bachelor Thesis in Economics. First Place, Research Award ExITAM XXV.</small>

- <span style="font-size: 0.9em;">[Geometry of Banach Spaces and Fixed Point Theory](https://isaacmeza.github.io/personal/files/mathematics_thesis_c.pdf)</span>
<small>Bachelor Thesis in Mathematics, in Spanish. Special Mention, Research Award ExITAM XXV.</small>


## Software

- <span style="font-size: 0.9em;">[nnpiv](https://nnpiv.readthedocs.io/en/latest/)</span>
<small>Python implementation of nested nonparametric instrumental variables. This package implements methods for estimating nonparametrically nested moment conditions. Related paper: [Meza and Singh](https://arxiv.org/abs/2112.14249).</small>

- <span style="font-size: 0.9em;">[tot_tut](https://github.com/isaacmeza/tot_tut)</span>
<small>Stata implementation for estimation of treatment-on-the-treated and treatment-on-the-untreated effects using the design in "Structured Payment in Pawnshop Borrowing: Mandates vs. Choice" by DiTraglia, McIntosh, Meza, Seira, and Sadka.</small>

```stata
net install tot_tut, from(https://raw.githubusercontent.com/isaacmeza/tot_tut/main) replace
```

- <span style="font-size: 0.9em;">[fan_park](https://github.com/isaacmeza/fan_park)</span>
<small>Stata implementation of sharp bounds on the distribution of treatment effects of a binary treatment developed in [Fan and Park (2009)](https://doi.org/10.1017/S0266466609990168).</small>

```stata
net install fan_park, from(https://raw.githubusercontent.com/isaacmeza/fan_park/main) replace
```