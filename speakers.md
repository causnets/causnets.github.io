---
layout: single
title: "Invited Speakers"
permalink: /speakers/
---

We have an exciting line-up of 4 invited speakers who will present on a diverse set of topics relevant to causal inference and networks.

## Christina Lee Yu, Cornell University

### TBD

<img src="/assets/images/causnets_speaker_cleeyu.jpg" alt="Christina Lee Yu" width="220" style="float:right; margin-left:20px; border-radius:10px;">

## Davide Viviano, Harvard University

### Causal Clustering: Design of Cluster experiments under network interference 

This paper studies the design of cluster experiments to estimate the global treatment effect in the presence of network spillovers. We provide a framework to choose the clustering that minimizes the worst-case mean-squared error of the estimated global effect. We show that optimal clustering solves a novel penalized min-cut optimization problem computed via off-the-shelf semi-definite programming algorithms. Our analysis also characterizes simple conditions to choose between any two cluster designs, including choosing between a cluster or individual-level randomization. We illustrate the method's properties using unique network data from the universe of Facebook's users and existing data from a field experiment.

**[Davide Viviano](https://dviviano.github.io/)** is an Assistant Professor at the Department of Economics at Harvard. His research combines economics and data science to develop or justify statistical methods for social‑science applications, with a focus on policy design and causal inference. Before joining Harvard, he spent a year at Stanford GSB as a post‑doctoral fellow sponsored by Guido Imbens. He received his Ph.D. from the Department of Economics in 2022 at UC San Diego and a Master's in Data Science in 2017 from Pompeu Fabra.

<img src="/assets/images/causnets_speaker_dviviano.jpg" alt="Davide Viviano" width="220" style="float:right; margin-left:20px; border-radius:10px;">

## Harsh Parikh, Yale University

### Transporting Treatment Effects Across Network

Causal inference in the presence of network interference is increasingly common in social science, social media and public health. Experiments are conducted on a set of source networks whose structure and composition may differ from target social networks of interest. We develop a framework for transporting treatment effects across networks, enabling researchers to generalize both direct and spillover effects estimated in an experimental source network to a target network where only covariates and network structure are observed. Our identification strategy relies on a residualization approach that disentangles direct and spillover effect functions from a partially linear structural model. Building on these, we propose a semiparametric estimator that leverages graph ML to learn low-dimensional network representations, kernel-weighted local regressions to estimate heterogeneous effect functions, and cross-fitting for valid inference with flexible machine-learning nuisance estimators. We further develop a sensitivity analysis framework that addresses potential misspecification of the network structure or the covariate summary function. We illustrate the method through simulations and an empirical application on material and child health intervention experimental studies in Honduras.

**[Harsh Parikh](https://harsh-parikh.github.io/)** is an Assistant Professor in the Department of Biostatistics at the Yale School of Public Health. He leads the Causal Evidence and Decisions Studio (CEADS), developing machine learning-aided causal inference approaches for high-stakes decision-making in complex environments. His research focuses on creating rigorous tools for estimating heterogeneous treatment effects, trustworthy methods that allow domain experts to validate causal assumptions, and domain-conscious approaches that bridge theory and practice in causal inference. Harsh's method work is used to address critical issues at the intersection of public health and social policy, including generalizing experimental evidence across populations, analyzing long-term economic impacts of health shocks, understanding environmental consequences of commodity price shifts, and optimizing treatment regimes. He holds a Ph.D. in Computer Science from Duke University and completed his postdoctoral fellowship at Johns Hopkins Bloomberg School of Public Health.

<img src="/assets/images/causnets_speaker_hparikh.png" alt="Harsh Parikh" width="220" style="float:right; margin-left:20px; border-radius:10px;">

## Shuangning Li, University of Chicago

### Covariate Adjustment Cannot Hurt: Treatment Effect Estimation under Interference with Low-Order Outcome Interactions

In randomized experiments, covariates are often used to reduce variance and improve the precision of treatment effect estimates. However, in many real world settings, interference between units, where one unit's treatment affects another's outcome, complicates causal inference. This raises a key question: how can covariates be effectively used in the presence of interference? Addressing this challenge is nontrivial, as direct covariate adjustment, such as through regression, can sometimes increase variance due to dependencies across units. In this paper, we study how to use covariate information to reduce the variance of treatment effect estimators under interference. We focus on the total treatment effect (TTE), defined as the difference in average outcomes when all units are treated versus when all are controlled. Our analysis is conducted under the neighborhood interference model and a low order interaction outcome model. Building on the SNIPE estimator from Cortez-Rodriguez et al. (2023), we propose a covariate adjusted SNIPE estimator and show that, under sparsity conditions on the interference network, the proposed estimator is asymptotically unbiased and has asymptotic variance no greater than that of the original SNIPE estimator. This parallels the classical result of Lin (2013) under the no interference assumption, where covariate adjustment does not worsen estimation precision. Importantly, our variance improvement result does not rely on strong assumptions about the covariates: the covariates may be arbitrarily dependent, affect outcomes across units, and depend on the interference network itself.

**[Shuangning Li](https://lsn235711.github.io/)** is an Assistant Professor of Econometrics and Statistics at the University of Chicago Booth School of Business. Before joining Booth, she was a postdoctoral fellow in the Department of Statistics at Harvard University. She received her Ph.D. in Statistics from Stanford University, where she was advised by Professors Emmanuel Candès and Stefan Wager. Prior to her doctoral studies, she earned a Bachelor of Science degree from the University of Hong Kong. Her research interests include causal inference, selective inference, and reinforcement learning.

<img src="/assets/images/causnets_speaker_sli.jpg" alt="Shuangning Li" width="220" style="float:right; margin-left:20px; border-radius:10px;">
