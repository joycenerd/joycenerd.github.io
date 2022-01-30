---
title: Generative Models as a Data Augmentation for Classification
collection: projects
type: "Final Project"
permalink: /projects/gen_aug
venue: "National Yang Ming Chiao Tung University"
date: 2021-09-09
github: "https://github.com/joycenerd/genrep_aug"
slide: "https://drive.google.com/file/d/1CFHCO4EvMaI3SkhEwThPgjzAdbFhxJF-/view?usp=sharing"
youtube: "https://youtu.be/y-v_K0sf_lA"
---

Use GAN steerability as an data augmentation technique.
<img src="/images/genaug_results.png">

In this project, we use GAN steerability as an data augmentation technique. The inspiration is coming from [GAN steerability](https://arxiv.org/pdf/1907.07171.pdf), and [GenRep](https://arxiv.org/pdf/2106.05258.pdf) these two papers. We investigate image transformation by exploring walks in the latent space of GAN. 

With a generator G and magnitude $\alpha$, we try to learn latent vectors $W_{steer}$ , which achieves the same effects of transformation $T$ in the image space. As a consequence, we can manipulate the latent space to do transformation. We implement 3 transformation, which are rotation, zoom and shift and color transformation.

For experiment, we compared the results of using only real data, real data + augmented data in image space, real data + augmented data in the latent space (GAN steer), and only generated data in the latent space. And we conclude that GAN steerability is a better data augmentation technique compare to transformation done in the data space

**More information of our implementation:** \
Code: <a href="https://github.com/joycenerd/genrep_aug" target="_blank"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a> \
Video: <a href="https://youtu.be/y-v_K0sf_lA" target="_blank"><i class="fab fa-fw fa-youtube zoom" aria-hidden="true"></i></a> \
Slides: <a href="https://drive.google.com/file/d/1CFHCO4EvMaI3SkhEwThPgjzAdbFhxJF-/view?usp=sharing" target="_blank"><i class="fas fa-fw fa-file-powerpoint zoom" aria-hidden="true"></i></a>
