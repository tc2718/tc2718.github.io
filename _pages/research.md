---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Constrained Learning for Causal Inference (job market paper)
**Tiffany Cai\***, Yuri Fonseca\*, Kaiwen Hou, Hongseok Namkoong (* denotes co-first authorship)

[Paper](http://arxiv.org/abs/2405.09493)

Forthcoming

Poster at [CODE@MIT
2024](https://ide.mit.edu/events/code24/)
and [ACIC 2024](https://sci-info.org/annual-meeting/)
<details>
  <summary>Summary</summary>
In challenging settings with limited overlap between treatment and control, causal estimators with
desirable asymptotic properties require ad hoc adjustments in order to produce stable estimates. In
contrast, simple plug-in estimators produce stable estimates but lack important asymptotic properties.

We propose a new estimation framework based on constrained optimization, that combines the best of
both worlds, and we demonstrate its superior empirical performance across several settings.
Our framework is compatible with modern machine learning, and we include settings with text covariates. 
We also include a theoretical example in which existing methods with desirable asymptotic properties converge
slower than our proposed method. 
</details>


## Active Exploration via Autoregressive Generation of Missing Data
**Tiffany Cai**, Hongseok Namkoong, Daniel Russo, Kelly W Zhang (authors listed in alphabetical order, project led by Kelly and Tiffany)


[Paper](https://arxiv.org/abs/2405.19466)

Poster at [Neurips 2024 Workshop: Bayesian Decision-Making and Uncertainty](https://gp-seminar-series.github.io/neurips-2024/)
and talk at [2024 Economics and AI+ML Meeting](https://www.econometricsociety.org/regional-activities/schedule/2024/08/13/2024-ESIFEconomics-and-AIML-Meeting)
<details>
  <summary>Summary</summary>
We propose a scalable solution to the problem of decision-making under uncertainty in a meta-bandit
setting by using a calibrated generative model to impute a sequence of missing (e.g. future) rewards.

Our proposed method is a principled implementation of Thompson (a.k.a. posterior) sampling.
We prove decision-making performance is controlled by the log loss of the generative model, and we
demonstrate on a news recommendation setting with text covariates.
</details>



## Diagnosing Model Performance Under Distribution Shift
**Tiffany Cai**, Steve Yadlowsky, Hongseok Namkoong

[Paper](https://arxiv.org/abs/2303.02011), [GitHub](https://github.com/namkoong-lab/disde), [Slides](https://docs.google.com/presentation/d/13KIGSJtxpqnEbdkPgGM9Hi-Eqw3hmOt5nigzZ-rkFWk/edit?usp=sharing)

Under revision at [Operations
Research](https://pubsonline.informs.org/journal/opre); presented at [FORC 2023](https://responsiblecomputing.org/forc-2023/), [INFORMS 2023](https://meetings.informs.org/wordpress/phoenix2023/)
<details>
  <summary>Summary</summary>
When your model performs worse out of distribution, should you use a domain adaptation method, or
do you need to collect more data? If the latter, from where should you collect more data?

We propose a new diagnostic using causal inference methods to attribute changes in performance to
X shifts and Y|X shifts. We demonstrate its utility in settings with tabular and image data.
</details>


## Tutorial: Modeling and Exploiting Data Heterogeneity under Distribution Shifts
Jiashuo Liu, **Tiffany Cai**, Peng Cui, Hongseok Namkoong

[Tutorial](https://neurips.cc/virtual/2023/tutorial/73953)

Presented at NeurIPS 2023
