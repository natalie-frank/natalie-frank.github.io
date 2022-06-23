---
layout: archive
title: "Publications and Preprints"
permalink: /publications/
author_profile: true
---
{% include base_path %}
**The Consistency of Adversarial Training for Binary Classification**, Authors: Natalie S. Frank, Jonathan Niles-Weed. <i>Submitted to Neurips</i>, 2022. [link](https://arxiv.org/abs/2206.09099)<br>
This paper studies statistical consistency and calibration in the adversarial setting. We show that when considering distributions absolutely continuous with respect to Lebesgue meaure, the supremum-based surrogate $\sup_{\|\mathbf x'-\mathbf x\|\leq \epsilon} \phi(yf(\mathbf x'))$ is consistent iff the surrogate $\phi$ is consistent for the standard (non-adversarial) classification problem.

**Existence and Minimax Theorems for Adversarial Surrogate Risks in Binary Classification**, Author: Natalie S. Frank <i>arxiv</i>, 2022. [link](https://arxiv.org/abs/2206.09098)<br>
We prove and existence, regularity, and minimax theorems for adversarial surrogate risks in the binary classification scenario. Our results explain some empirical observations on adversarial robustness from prior work and suggest new directions in algorithm development. Furthermore, our results extend previously known existence and minimax theorems for the adversarial classification risk to surrogate risks.

**On the Existence of the Adversarial Bayes Classifier**,  Authors: Pranjal Awasthi, Natalie Frank, Mehryar Mohri. <i>NeurIPS</i>, 2021, **Spotlight Presentation**. [Extended Version](https://arxiv.org/pdf/2112.01694.pdf)<br>
We prove that there exist minimizers to the adversarial risk which we call the *adversarial Bayes classifier* with nice reguarity properties. The results of the original paper did not apply to non-strictly convex norms. The extended version of the paper extends these results to all possible norms.

**Calibration and Consistency of Adversarial Surrogate Losses**,  Authors: Pranjal Awasthi, Natalie Frank, Anqi Mao, Mehryar Mohri, Yutao Zhong. <i>NeurIPS</i>, 2021, **Spotlight Presentation**. [link](https://arxiv.org/abs/2104.09658)<br>
This paper studies statistical consistency and calibration in the adversarial setting. One major highlight is that we show no continuous surrogate loss is statistically consistent in the adversarial setting when learning over a well-motivated linear function class.

**Adversarial Learning Guarantees for Linear Hypotheses Sets and Neural Networks**,  Authors: Pranjal Awasthi, Natalie Frank, Mehryar Mohri. <i>ICML</i>, 2020. [link](http://proceedings.mlr.press/v119/awasthi20a.html)<br>
Consider perturbations measured in $\ell_r$ norm. We give bounds on the adversarial Rademacher complexity of linear classes, a single ReLU unit, feed-forward neural networks.

**The Frog Model on Trees with Drift**,  Authors: Erin Beckman, Natalie Frank, Yufeng Jiang, Matthew Junge, Si Tang. <i>Electronic Communications in Probability</i>, 2019. [link](https://projecteuclid.org/journals/electronic-communications-in-probability/volume-24/issue-none/The-frog-model-on-trees-with-drift/10.1214/19-ECP235.full)<br>
Consider the one-per-cite frog model on a $d$-ary tree with drift towards the root. We show that for any $d$, the frog model is recurrent with drift larger than or equal to $0.4155$. 
  
# Expository Notes
  
**On the Rademacher Complexity of Linear Hypothesis Sets**, Authors: Pranjal Awasthi, Natalie Frank, Mehryar Mohri. 2020. [link](https://arxiv.org/abs/2007.11045)<br>
We give upper and lower bounds on the empirical Rademacher complexity of the linear hypothesis classes with weight factors bounded in $\ell_p$ norm. These were the best known bounds at time of writing. Previously, bounds were known only for $1\leq p \leq 2$.
