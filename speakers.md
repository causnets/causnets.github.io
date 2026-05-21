---
layout: single
title: "Speakers"
permalink: /speakers/
---

## Invited Talks

### Christina Lee Yu, Cornell University

#### Optimizing Cluster Randomized Designs on Networks with Homophily

Cluster randomized designs have been proposed to mitigate bias arising from network interference. However, if the network exhibits homophily, we show that the standard objectives for constructing clusterings are insufficient. In particular, we give two scenarios in which the mean squared error of estimating the total treatment effect is minimized by clusters that balance between an objective that encourages well separated clusters versus an objective that encourages covariate balance. These two objectives are in tension with each other for networks that exhibit homophily, highlighting the need for new clustering algorithms that carefully balance between these objectives. The results in this talk are from the papers: "Analysis of Two-Stage Rollout Designs with Clustering for Causal Inference under Network Interference" and "Optimal Design under Interference, Homophily, and Robustness Trade-offs".

<img src="/assets/images/causnets_speaker_cleeyu.jpg" alt="Christina Lee Yu" width="220" style="float:right; margin-left:20px; border-radius:10px;">

**[Christina Lee Yu](https://cleeyu.orie.cornell.edu/)** is an Assistant Professor at Cornell University in the School of Operations Research and Information Engineering. She is also an Amazon scholar. Prior to Cornell, she was a postdoc at Microsoft Research New England. She received her PhD and MS in Electrical Engineering and Computer Science from Massachusetts Institute of Technology, and her BS in Computer Science from California Institute of Technology. She is a recipient of the NSF CAREER Award, ACM SIGMETRICS Rising Stars Award, Intel Rising Stars Award, JPMorgan Faculty Research Award, and honorable mention for the 2018 INFORMS Dantzig Dissertation Award. Her work is supported by grants from the National Science Foundation and the Air Force Office of Scientific Research.

<div style="clear: both;"></div>

### Davide Viviano, Harvard University

#### Causal Clustering: Design of Cluster experiments under network interference 

This paper studies the design of cluster experiments to estimate the global treatment effect in the presence of network spillovers. We provide a framework to choose the clustering that minimizes the worst-case mean-squared error of the estimated global effect. We show that optimal clustering solves a novel penalized min-cut optimization problem computed via off-the-shelf semi-definite programming algorithms. Our analysis also characterizes simple conditions to choose between any two cluster designs, including choosing between a cluster or individual-level randomization. We illustrate the method's properties using unique network data from the universe of Facebook's users and existing data from a field experiment.

<img src="/assets/images/causnets_speaker_dviviano.jpg" alt="Davide Viviano" width="220" style="float:right; margin-left:20px; border-radius:10px;">

**[Davide Viviano](https://dviviano.github.io/)** is an Assistant Professor at the Department of Economics at Harvard. His research combines economics and data science to develop or justify statistical methods for social‑science applications, with a focus on policy design and causal inference. Before joining Harvard, he spent a year at Stanford GSB as a post‑doctoral fellow sponsored by Guido Imbens. He received his Ph.D. from the Department of Economics in 2022 at UC San Diego and a Master's in Data Science in 2017 from Pompeu Fabra.

<div style="clear: both;"></div>

### Harsh Parikh, Yale University

#### Transporting Treatment Effects Across Network

Causal inference in the presence of network interference is increasingly common in social science, social media and public health. Experiments are conducted on a set of source networks whose structure and composition may differ from target social networks of interest. We develop a framework for transporting treatment effects across networks, enabling researchers to generalize both direct and spillover effects estimated in an experimental source network to a target network where only covariates and network structure are observed. Our identification strategy relies on a residualization approach that disentangles direct and spillover effect functions from a partially linear structural model. Building on these, we propose a semiparametric estimator that leverages graph ML to learn low-dimensional network representations, kernel-weighted local regressions to estimate heterogeneous effect functions, and cross-fitting for valid inference with flexible machine-learning nuisance estimators. We further develop a sensitivity analysis framework that addresses potential misspecification of the network structure or the covariate summary function. We illustrate the method through simulations and an empirical application on material and child health intervention experimental studies in Honduras.

<img src="/assets/images/causnets_speaker_hparikh.png" alt="Harsh Parikh" width="220" style="float:right; margin-left:20px; border-radius:10px;">

**[Harsh Parikh](https://harsh-parikh.github.io/)** is an Assistant Professor in the Department of Biostatistics at the Yale School of Public Health. He leads the Causal Evidence and Decisions Studio (CEADS), developing machine learning-aided causal inference approaches for high-stakes decision-making in complex environments. His research focuses on creating rigorous tools for estimating heterogeneous treatment effects, trustworthy methods that allow domain experts to validate causal assumptions, and domain-conscious approaches that bridge theory and practice in causal inference. Harsh's method work is used to address critical issues at the intersection of public health and social policy, including generalizing experimental evidence across populations, analyzing long-term economic impacts of health shocks, understanding environmental consequences of commodity price shifts, and optimizing treatment regimes. He holds a Ph.D. in Computer Science from Duke University and completed his postdoctoral fellowship at Johns Hopkins Bloomberg School of Public Health.

<div style="clear: both;"></div>

### Shuangning Li, University of Chicago

#### Covariate Adjustment Cannot Hurt: Treatment Effect Estimation under Interference with Low-Order Outcome Interactions

In randomized experiments, covariates are often used to reduce variance and improve the precision of treatment effect estimates. However, in many real world settings, interference between units, where one unit's treatment affects another's outcome, complicates causal inference. This raises a key question: how can covariates be effectively used in the presence of interference? Addressing this challenge is nontrivial, as direct covariate adjustment, such as through regression, can sometimes increase variance due to dependencies across units. In this paper, we study how to use covariate information to reduce the variance of treatment effect estimators under interference. We focus on the total treatment effect (TTE), defined as the difference in average outcomes when all units are treated versus when all are controlled. Our analysis is conducted under the neighborhood interference model and a low order interaction outcome model. Building on the SNIPE estimator from Cortez-Rodriguez et al. (2023), we propose a covariate adjusted SNIPE estimator and show that, under sparsity conditions on the interference network, the proposed estimator is asymptotically unbiased and has asymptotic variance no greater than that of the original SNIPE estimator. This parallels the classical result of Lin (2013) under the no interference assumption, where covariate adjustment does not worsen estimation precision. Importantly, our variance improvement result does not rely on strong assumptions about the covariates: the covariates may be arbitrarily dependent, affect outcomes across units, and depend on the interference network itself.

<img src="/assets/images/causnets_speaker_sli.jpg" alt="Shuangning Li" width="220" style="float:right; margin-left:20px; border-radius:10px;">

**[Shuangning Li](https://lsn235711.github.io/)** is an Assistant Professor of Econometrics and Statistics at the University of Chicago Booth School of Business. Before joining Booth, she was a postdoctoral fellow in the Department of Statistics at Harvard University. She received her Ph.D. in Statistics from Stanford University, where she was advised by Professors Emmanuel Candès and Stefan Wager. Prior to her doctoral studies, she earned a Bachelor of Science degree from the University of Hong Kong. Her research interests include causal inference, selective inference, and reinforcement learning.

## Contributed Talks

### Souhardya Sengupta, Harvard University

#### Low-rank Covariate Balancing Estimators under Interference

In observational studies, causal effect estimation becomes difficult when the outcome of one unit depends on the treatments of others. Existing approaches rely on inverse-probability weighting (IPW) with estimated propensity scores which can lead to misspecification and bias, especially when treatment uptake exhibits complex dependencies across units. To address this challenge, we propose a general class of covariate balancing estimators under interference. Existing balancing estimators are limited to settings without spillover effects. We develop our approach under a notion of low-rank structure of potential outcomes, which encompasses a broad class of commonly used assumptions, including anonymous, nearest neighbor, and additive interference, while allowing for more complex, study-specific forms of dependence. Our proposed balancing estimator is asymptotically normal with a consistent variance estimator, leading to asymptotically valid confidence intervals and a data-driven procedure for selecting among candidate low-rank structures. Simulation and empirical studies demonstrate that the proposed estimator is substantially more efficient than the standard IPW estimator.

### Liang Zhong, University of Hong Kong

#### Unconditional Randomization Tests for Interference

Researchers are often interested in the existence and extent of interference between units when conducting causal inference or designing policy. However, testing for interference presents significant econometric challenges, particularly due to complex clustering patterns and dependencies that can invalidate standard methods. This paper introduces the pairwise imputation-based randomization test (PIRT), a general and robust framework for assessing the existence and extent of interference in experimental settings. PIRT employs unconditional randomization testing and pairwise comparisons, enabling straightforward implementation and ensuring finite-sample validity under minimal assumptions about network structure. The method's practical value is demonstrated through an application to a large-scale policing experiment in Bogota, Colombia (Blattman et al., 2021), which evaluates the effects of hotspot policing on crime at the street segment level. The analysis reveals that increased police patrolling in hotspots significantly displaces violent crime, but not property crime. Simulations calibrated to this context further underscore the power and robustness of PIRT.

### Alden Cheng, National Bureau of Economic Research and University of Illinois Urbana-Champaign

#### From Peer Effects to Network Evolution: Evidence from the Illinois Workplace Wellness Study

In this paper, we provide causal evidence that health behavior propagates through links in friendship networks (peer effects), and that external interventions can induce changes in the network structure itself (network evolution). We do so by designing and implementing a large-scale randomized controlled trial (RCT)—the Illinois Workplace Wellness Study—on 4,834 employees at a large public university. We measure participants’ friendship networks at baseline in 2016 and in two follow-up surveys (in 2017 and 2018). Study participants are randomized into treatment and control groups at baseline, with treatment conferring eligibility for health screenings. We estimate that among treated individuals, each additional friend assigned to the treatment group increases own probability of participating in health screenings by 4.2 percentage points, and that each additional friend’s participation increases own participation probability by 6.4 percentage points. Moreover, we find that being treated at baseline increases one’s probability of being listed as a friend by coworkers in the future by about 9 percent, and that the intervention increased homophily in the friendship network.

## Lightning Talks

### 1. Zhaolu Liu, Imperial College London

#### Information-theoretic signatures of causality in Bayesian networks and hypergraphs

Traditional causal discovery frameworks rely on pairwise graphs, limiting direct multivariate reasoning. Partial Information Decomposition (PID) offers a higher-order alternative by decomposing source information into redundant, unique, and synergistic components, but its mathematical connection to causal structure has remained undeveloped. Here, we establish the first theoretical correspondence between PID components and causal structure in both Bayesian networks and hypergraphs. For Bayesian networks, unique information identifies direct causal neighbors, while synergy reveals collider relationships. This enables a localist causal discovery paradigm: local structure can be recovered directly from a variable's immediate informational footprint, eliminating the need for global graph searches. Extending this to Bayesian hypergraphs, we prove PID signatures distinguish parents, children, co-heads, and co-tails, revealing a novel multi-tail collider effect. Ultimately, our results position PID as a rigorous, model-agnostic foundation for inferring pairwise and higher-order causal structures through a fundamentally local, information-theoretic lens.

### 2. Sohom Bhattacharya, University of Florida

#### Causal effect estimation under network interference: mean-field methods and beyond

We study causal effect estimation under network interference using a chain graph framework, allowing long-range interaction across the network. We first establish a fundamental computational barrier: without additional assumptions, no universal algorithm can efficiently evaluate causal effects in this setting. Under a high-temperature condition, we develop provably consistent polynomial-time methods for two settings: mean-field networks via a scalable iterative algorithm, and Gaussian weighted networks via Approximate Message Passing. Model parameters are estimated using maximum pseudo-likelihood, achieving consistency, and we show that plug-in estimators are consistent in this regime. Beyond high temperature, for dense graphs and random Gaussian interactions, we show treatment effects converge to deterministic limits, and design polynomial-time algorithms that remain consistent even in low-temperature regimes where standard MCMC methods fail. This is joint work with Subhabrata Sen. (Harvard University)

### 3. Simiao Jiao, Duke University

#### Estimating Heterogeneous Treatment Effects Using Network Data

This paper studies causal effect estimation for binary treatments when effects vary across latent groups that are not directly observed but are partially revealed by noisy network data. Ignoring hidden communities can bias average treatment effect estimates, while naively using estimated labels can introduce misclassification bias. We propose a network-assisted framework that detects communities, ranks units by a reliability score such as node degree, and estimates subgroup conditional average treatment effects on high-confidence subsets using augmented inverse probability weighting. The estimates recover the original subgroup effects under an independence condition, or otherwise define local effects among reliable network units. We prove asymptotic normality under controlled label error, derive valid thresholds for stochastic block and degree-corrected block models, and develop a data-driven Lepski-type rule that balances misclassification bias and sampling variance.

### 4. Marios Papamichalis, Yale University

#### Educational Intervention Re-Wires Social Interactions in Village Networks

Social networks transmit information and support collective action, but interventions that use them may also reshape them. We study this in a randomized trial in 110 remote Honduran villages involving 8,331 people. A 22-month maternal, neonatal, and child health education program was assigned at village dosages of 0%, 5%, 10%, 20%, 30%, 50%, 75%, or 100% of households. Comparing pre- and post-intervention networks, we find that the intervention rewired health-advice ties without substantially changing village-wide degree distributions. In low-dosage villages, treated individuals tended to lose ties to untreated people they had previously consulted for health advice. In high-dosage villages, treated individuals gained ties. The mechanism is dyadic: treated–treated ties persisted or formed, while treated–untreated ties dissolved. Health-knowledge gains partly increased tie persistence and formation, but most rewiring was not explained by knowledge alone. These patterns persisted three years later and extended to friendship and financial ties.

### 5. JungHo Lee, Carnegie Mellon University

#### Partial identification of Average Treatment Effects under Unknown Interference

In many applications, especially in the social and epidemiological sciences, interference is likely present but the underlying network is often unobserved. While estimation of causal effects is sometimes possible in experiments without network information, it can be much more challenging in observational studies where treatment assignment may depend on latent neighborhood context and unmeasured confounding becomes concerning. We propose a partial identification approach for the expected average treatment effect (EATE) in observational studies when the network is unknown by extending marginal sensitivity models to interference. The key idea is to impose the model at the level of a randomly selected unit, which yields a pooled model that avoids imposing any homogeneity assumptions on the data. This allows the EATE to be bounded using sharp marginal sensitivity model results developed for the ordinary no-interference setting. We also discuss how partial information about the interference structure can be incorporated through a hierarchical extension that separates individual-level and network-level hidden confounding, potentially yielding sharper and more interpretable bounds.

### 6. Vydhourie Thiyageswaran, University of Washington

#### Optimal Design under Interference, Homophily, and Robustness

To minimize the mean squared error (MSE) in global average treatment effect (GATE) estimation under network interference, a popular approach is to use a cluster-randomized design. However, in the presence of homophily, which is common in social networks, cluster randomization can instead increase the MSE. We develop a novel potential outcomes model that accounts for interference, homophily, and heterogeneous variation. In this setting, we establish a framework for optimizing designs for worst-case MSE under the Horvitz-Thompson estimator. This leads to an optimization problem over the covariance matrices of the treatment assignment, trading off interference, homophily, and robustness. We frame and solve this problem using two complementary approaches. The first involves formulating a semidefinite program (SDP) and employing Gaussian rounding, in the spirit of the Goemans-Williamson approximation algorithm for MAXCUT. The second is an adaptation of the Gram-Schmidt Walk, a vector-balancing algorithm which has recently received much attention. Finally, we evaluate the performance of our designs through various experiments on simulated and real network data.

### 7. Yechan Park, Harvard University

#### Decomposition of Spillover Effects Under Misspecification: Pseudo-True Estimands and a Local-Global Extension

Applied work under interference often models outcomes as functions of own treatment and a low-dimensional exposure mapping of others’ treatments, even when that mapping is misspecified. We ask what policy object such procedures target. Taking the marginal policy effect as primitive, we show that any chosen exposure mapping induces a unique pseudo-true outcome model: the best approximation to the underlying potential outcomes among functions that depend only on that mapping. This yields a decomposition of the marginal policy effect into exposure-based direct and spillover effects, and each component optimally approximates its oracle counterpart, with a sign-preserving interpretation under monotonicity. We apply this to a concrete setting in which outcomes depend on both network spillovers and a global equilibrium channel, while the analyst may model only one. In this setting, we obtain a sharper asymptotic decomposition into direct, local, and global components, implying that existing estimators recover their oracle channel-specific effects even when the other channel is omitted from the maintained model. We illustrate the framework in a large cash-transfer experiment.

### 8. Abhinandan Dalal, University of Pennsylvania

#### Two-Fold Double Robust Treatment Effect Estimation with Unknown/Mismeasured Network Interference

Causal inference without SUTVA often requires knowledge of the underlying network, however the true network may be unknown, partially observed, or mismeasured, raising concerns about the validity of causal conclusions. We study estimation of the direct treatment effect in observational settings under such uncertainty. Under a novel conditional independence of treatment assignment assumption, where treatment depends only on unit-level covariates, we show that the classic AIPW estimator recovers the direct effect and retains its model double-robustness property. We further develop a novel notion of sparsity-dependence double robustness, distinct from model robustness, under which reliable inference is possible when either the network is sufficiently sparse or cross-unit dependence is adequately weak, allowing each condition to compensate for the other. Our framework accommodates arbitrary sources of interference, including homophily and contagion, without complete knowledge of the network. We also provide conditions for valid variance estimation under partially observed or mismeasured networks, enabling reliable inference when network data are incomplete or approximate.

### 9. Heejong Bong, Purdue University

#### Causal Inference with Noisy Network Representations of Latent Interference Structure

We study causal inference under interference when the observed network is a noisy measurement of an underlying interaction structure that governs spillovers. Standard network interference methods restrict interference to observed neighbors, but many applications involve latent interactions that create influence through weak or unobserved ties. Modeling interference through a latent interaction matrix can be realistic but leads to severe positivity issues for propensity based estimators that rely on high dimensional joint assignment probabilities. We propose a kernel surrogate approach that replaces the intractable joint propensity score by locally aggregated propensities defined through an egocentric distance to a target intervention pattern. The resulting estimator resembles a doubly robust estimator based on augmented inverse propensity weighting, remains usable under diffuse or global interference, and empirically improves accuracy under noisy network measurements compared to standard network interference methods.

### 10. Daniel Guerrero, Purdue University

#### Mapping the Causal Architecture of Alcohol-Related Problems Across Adulthood

Alcohol-related problems arise from complex interactions among impulsive traits, family history, demographics, and brain network organization, yet their causal structure remains poorly understood. We applied Linear Non-Gaussian Acyclic Models to characterize causal relationships underlying alcohol-related problems across adulthood. Using data from 1202 participants, we estimated causal models across 29 overlapping age windows to identify evolving risk and resilience factors. In a subset (N=229), we incorporated resting-state functional connectivity among salience, frontoparietal, and default mode networks. Alcohol consumption remained a persistent causal risk factor, while education emerged as a prominent resilience factor, particularly during mid-adulthood. Family history density and urgency-related impulsivity showed age-dependent causal effects. Increased salience–frontoparietal connectivity elevated sensation seeking, alcohol consumption, and alcohol-related problems. These findings identify developmentally dynamic and neurobiologically grounded intervention targets, demonstrating the utility of causal modeling for disentangling multivariate mechanisms of AUD vulnerability.

### 11. Fei Fang, Yale University

#### Design-Based Weighted Regression Estimators for Average and Conditional Spillover Effects

When individuals engage in social or physical interactions, a unit’s outcome may depend on the treatments received by others. In such interference environments, we provide a unified framework characterizing a broad class of spillover estimands as weighted averages of unit-to-unit spillover effects, with estimand-specific weights. We then develop design-based weighted least squares (WLS) estimators for both average and conditional spillover effects. We introduce three nonparametric estimators under the dyadic, sender, and receiver perspectives, which distribute the estimand weights differently across the outcome vector, design matrix, and weight matrix. For the average-type estimands, we show that all three estimators are equivalent to the Hájek estimator.  For conditional spillover effects, we establish conditions under which the estimands are consistent for the target conditional spillover effects. We further derive concentration inequalities, a central limit theorem, and conservative variance estimators in an asymptotic regime where both the number of clusters and cluster sizes grow.

### 12. Elena Dal Torrione, Yale University

#### Optimal Plug-in Treatment Rules under Heterogeneous Network Interference

This paper studies optimal treatment policies under heterogeneous network interference, where treating different individuals affects welfare differently through their direct response and influence on others. In settings without interference, the welfare-maximizing policy treats individuals with positive conditional average treatment effects. Under interference, however, individual outcomes depend on others’ treatments, and simple plug-in treatment rules are generally unavailable without further assumptions on the underlying potential outcome structure. We  derive general optimality conditions in terms of conditional direct and indirect effects for units with given covariates, and show that, unlike no-interference settings, under interference optimal treatment rules may be stochastic. Next, we propose a quadratic outcome model that incorporates pairwise treatment interactions and nests standard linear-exposure models. We derive conditions under which the optimal policy admits a closed-form characterization and discuss implications for plug-in treatment rule estimation. 
