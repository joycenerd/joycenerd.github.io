---
title: RSNA Pneumonia Detection
collection: projects
type: "Final Project"
permalink: /projects/rsna_detect
venue: "National Yang Ming Chiao Tung University"
date: 2022-01-06
github: "https://github.com/joycenerd/rsna-pneumonia-detection"
slide: "https://drive.google.com/file/d/1iMC_G35EuJ9ObWxtH5yVydpKOANabI_2/view?usp=sharing"
paperurl: "https://drive.google.com/file/d/1S0MRRq2Ej19p18ZYs3y1Lb5WDHZN7xLV/view?usp=sharing"
---

Design a two stage method to solve RSNA Pneumonia detection challenge on Kaggle.
<img src="/images/rsna_cls_det.png">

In the project, we participated the RSNA Pneumonia Detection Challenge on Kaggle. The challenge is about to detect a visual signal for pneumonia in medical images. The dataset contains about 30,000 medical images, which belong to 3 different classes. The classes are Lung Opacity, No Lung Opacity / Not Normal and Normal respectively. Lung Opacity means the patient is diagnosed with pneumonia. No Lung Opacity / Not Normal means the patient is diagnosed as other lung diseases but not pneumonia. The Normal class means no disease is detected. As a consequence, it is not easy to detect pneumonia with these data. First of all, the No Lung Opacity / Not Normal class may mislead the model. Secondly, the data is extremely imbalanced, there is only 6,000 data that is diagnosed with pneumonia. 

We have tried detection only method, first classification then detection method and ensembling. We get the best results when using EficientNet as classification model with 0.2 classfication probability threshold when testing, and YOLOR as detection model, and boost the final accuracy 2% by resizing the predicted bounding box to 87.5% of the original size. We think our method's main contribution is to do classification first then detection to reduce false positive results. 

We have done many experiments with different combinations and have some interesting findings as well. Checkout our report for more details.

**More information of our implementation:** \
Report: <a href="https://drive.google.com/file/d/1S0MRRq2Ej19p18ZYs3y1Lb5WDHZN7xLV/view?usp=sharing" target="_blank"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> \
Code: <a href="https://github.com/joycenerd/rsna-pneumonia-detection" target="_blank"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a> \
Slides: <a href="https://drive.google.com/file/d/1iMC_G35EuJ9ObWxtH5yVydpKOANabI_2/view?usp=sharing" target="_blank"><i class="fas fa-fw fa-file-powerpoint zoom" aria-hidden="true"></i></a>