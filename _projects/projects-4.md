---
title: Reimplemenatation Challenge -- Maximum a Posteriori Policy Optimisation
collection: projects
type: "Final Project"
permalink: /projects/mpo
venue: "National Yang Ming Chiao Tung University"
date: 2021-06-30
github: "https://github.com/joycenerd/MPO_Reimplementation"
paperurl: "/files/Replication__MAXIMUM_A_POSTERIORI_POLICY_OPTIMISATION.pdf"
slide: "https://drive.google.com/file/d/1B-7gZG1zGAiyXOhbjj3MUnvqWFNYPmlD/view?usp=sharing"
---

Reimplement the paper Maximum a Posteriori Policy Optimisation
<img src="/images/hopper_mse.gif">

The author of the paper provided a new RL training strategy via training model and auxiliary distribution. The main contribution is the idea transformation from inference to general RL task. The developed method is off-policy, so the training process is efficient by replaying the experience from buffer instead of interacting with the environment again and again, which is time consuming.

Furthermore, the author offered their theory with detailed explanation, helping the audience understand the theory behind quickly.Nevertheless, there is a typo in the section D of the appendix:

$$
\exp(-\frac{\eta-\gamma}{\eta})=\int\pi(a|s,\theta_i)\exp(\frac{Q_{\theta_i}(a,s)}{\eta})da
$$

should be correct as

$$
\exp(\frac{\eta-\gamma}{\eta})=\int\pi(a|s,\theta_i)\exp(\frac{Q_{\theta_i}(a,s)}{\eta})da
$$

Apart from replicating the algorithm from the paper, we also apply numerical tricks to stabilize the training process. Moreover, We are considering improving the method by modifying the E-step. In E-step, the author first set $q=\pi_{\theta_i}$ when constructing the Q-value function, leading to the optimization in one step. (Because we want to optimize $q$ in E-step, but Q-value function is forced to follow $\pi_{\theta_i}$, not the optimized $q$) This modification might be hard to implement due to the dramatically increasing complexity. However, if the above problem is overcome, the algorithm might benefit from faster convergence rate, which alleviate the slow converging issue in off-policy algorithm.

**More information of our implementation:** \
Report: <a href="/files/Replication__MAXIMUM_A_POSTERIORI_POLICY_OPTIMISATION.pdf" target="_blank"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> \
Code: <a href="https://github.com/joycenerd/MPO_Reimplementation" target="_blank"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a> \
Slides: <a href="https://drive.google.com/file/d/1B-7gZG1zGAiyXOhbjj3MUnvqWFNYPmlD/view?usp=sharing" target="_blank"><i class="fas fa-fw fa-file-powerpoint zoom" aria-hidden="true"></i></a>
