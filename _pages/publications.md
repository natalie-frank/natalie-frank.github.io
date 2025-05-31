---
layout: archive
title: "Publications and Preprints"
permalink: /publications/
author_profile: true
---
{% include base_path %}

**The Price of Implicit Bias in Adversarially Robust Generalization** Authors: Nikolaos Tsilivis, Natalie Frank, Nathan Srebro, Julia Kempe. <i> NeurIps <i/>, 2024. [link](https://arxiv.org/abs/2406.04981) <br>
In the setting of adversarial classification and linear models, we study the connection between adversarial generalization, the optimization algorithm, and model architecture.


**Adversarial Consistency and the Uniqueness of the Adversarial Bayes Classifier** Authors: Natalie Frank <i> European Journal of Applied Mathematics </i>, 2024. [link](https://doi.org/10.1017/S0956792525000038) <br>
This paper connects the statistical consistency of risks for adversarial learning with the uniqueness of the adversarial Bayes classifier. 

**A Notion of Uniqueness for the Adversarial Bayes Classifier** Authors: Natalie Frank <i> In revision at SIMODS </i>, 2024. [link](https://arxiv.org/abs/2404.16956)<br> We propose a new notion of uniqueness for the adversarial Bayes classifier that defines an equivalence class on sets in the setting of binary classification. Analyzing this concept produces a simple procedure for computing all adversarial Bayes classifiers for a well-motivated family of one dimensional data distributions.  

**Robust Explanations for Deep Neural Networks via Pseudo Neural Tangent Kernel Surrogate Models** Authors: Andrew Engel, Zhichao Wang, Natalie S. Frank, Ioana Dumitriu, Sutanay Choudhury, Anand Sarwate, Tony Chiang. <i> ICLR </i>, 2024. [link](https://arxiv.org/abs/2305.14585) <br>
This paper compares neural nets and GLMs trained with a pNTK, a normalized NTK summed across classes. Our experiments show that such a GLM is a good surrogate model for the neural net. We compute data attributions for these surrogate models under a data poisoning attack, and show that these attributions are more accurate than several alternatives. 

**The Adversarial Consistency of Surrogate Risks for Binary Classification**, Authors: Natalie S. Frank, Jonathan Niles-Weed. <i>NeurIps</i>, 2024. [link](https://arxiv.org/abs/2305.09956)<br>
This paper studies statistical consistency in the adversarial setting. We show that the supremum-based surrogate $\sup_{\|\mathbf x'-\mathbf x\|\leq \epsilon} \phi(yf(\mathbf x'))$ is consistent for all data distributions iff the surrogate $\phi$ satisfies $\inf_\alpha \phi(\alpha)+\phi(-\alpha)<2\phi(0)$.

**Existence and Minimax Theorems for Adversarial Surrogate Risks in Binary Classification**, Author: Natalie S. Frank <i>JMLR</i>, 2024. [link](https://arxiv.org/abs/2206.09098)<br>
We prove and existence, regularity, and minimax theorems for adversarial surrogate risks in the binary classification scenario. Our results extend previously known existence and minimax theorems for the adversarial classification risk to surrogate risks.

**On the Existence of the Adversarial Bayes Classifier**,  Authors: Pranjal Awasthi, Natalie Frank, Mehryar Mohri. <i>NeurIPS</i>, 2021, **Spotlight Presentation**. [link](https://arxiv.org/pdf/2112.01694.pdf)<br>
We prove that there exist minimizers to the adversarial risk which we call the *adversarial Bayes classifier* with nice reguarity properties. The results of the original paper did not apply to non-strictly convex norms. The extended version of the paper extends these results to all possible norms.

**Calibration and Consistency of Adversarial Surrogate Losses**,  Authors: Pranjal Awasthi, Natalie Frank, Anqi Mao, Mehryar Mohri, Yutao Zhong. <i>NeurIPS</i>, 2021, **Spotlight Presentation**. [link](https://arxiv.org/abs/2104.09658)<br>
This paper studies statistical consistency and calibration in the adversarial setting. One major highlight is that we show no continuous surrogate loss is statistically consistent in the adversarial setting when learning over a well-motivated linear function class.

**Adversarial Learning Guarantees for Linear Hypotheses Sets and Neural Networks**,  Authors: Pranjal Awasthi, Natalie Frank, Mehryar Mohri. <i>ICML</i>, 2020. [link](http://proceedings.mlr.press/v119/awasthi20a.html)<br>
Consider perturbations measured in $\ell_r$ norm. We give bounds on the adversarial Rademacher complexity of linear classes, a single ReLU unit, feed-forward neural networks.

**The Frog Model on Trees with Drift**,  Authors: Erin Beckman, Natalie Frank, Yufeng Jiang, Matthew Junge, Si Tang. <i>Electronic Communications in Probability</i>, 2019. [link](https://projecteuclid.org/journals/electronic-communications-in-probability/volume-24/issue-none/The-frog-model-on-trees-with-drift/10.1214/19-ECP235.full)<br>
Consider the one-per-cite frog model on a $d$-ary tree with drift towards the root. We show that for any $d$, the frog model is recurrent with drift larger than or equal to $0.4155$. 
  
# Other
  
**Expository Note: On the Rademacher Complexity of Linear Hypothesis Sets**, Authors: Pranjal Awasthi, Natalie Frank, Mehryar Mohri. 2020. [link](https://arxiv.org/abs/2007.11045)<br>
We give upper and lower bounds on the empirical Rademacher complexity of the linear hypothesis classes with weight factors bounded in $\ell_p$ norm for $p \in [1,\infty]$. These were the best known bounds at time of writing. Previously, bounds were known only for $p \in [1,2]$.

**Thesis:** [**Understanding Adversarial Risks**](https://raw.githubusercontent.com/natalie-frank/natalie-frank.github.io/master/files/misc/Thesis.pdf): The theory of risks in the non-adversarial setting is well understood, and includes results such as formulas a characterization of statistical consistency and formulas for minimizers. Some of these results are extended to the adversarial setting.  
