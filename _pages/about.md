---
permalink: /
title: "Zhi-Yi Chin"
# excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a research assistant at National Yang Ming Chiao Tung University (NYCU) in Taiwan, where I specialize in the field of machine learning model safety, with a particular focus on multimodal applications. I have had the privilege of working alongside Professor [Wei-Chen (Walon) Chiu](https://walonchiu.github.io) at NYCU and collaborating with Dr. [Pin-Yu Chen](https://sites.google.com/site/pinyuchenpage) on cutting-edge research in this domain.

My academic journey led me to NYCU, where I completed my Master of Science degree under the guidance of Professor [Wei-Chen (Walon) Chiu](https://walonchiu.github.io). Prior to that, I earned my Bachelor of Science degree from National Chung Cheng University, where I had the privilege of being advised by Professor [Chen-Kuo (Adrian) Chiang](https://www.cs.ccu.edu.tw/~ckchiang/).

I am passionate about advancing the field of machine learning and model safety, and I am committed to making meaningful contributions to this exciting and rapidly evolving field. Please feel free to explore my academic journey and research interests on this website. 

## Publications
For a comprehensive list of my publications, please refer to my Curriculum Vitae (CV). \
($^\dagger$ indicates equal contribution)
<table>
  <tr>
    <td><img src="/images/p4d_teaser.png" width="200"></td>
    <td style="font-size: 17px; line-height: 1.4em;">
      <a href="https://arxiv.org/abs/2309.06135" target="_blank"><strong>Prompting4Debugging: Red-Teaming Text-to-Image Diffusion Models by Finding Problematic Prompts</strong></a><br/><strong>Zhi-Yi Chin</strong><sup>&dagger;</sup>, Chieh-Ming Jiang<sup>&dagger;</sup>, Pin-Yu Chen, Ching-Chun Huang, Wei-Chen Chiu<br/><i>arXiv 2023</i><br/><a href="https://joycenerd.github.io/prompting4debugging/" target="_blank"><i class="fa fa-fw fa-home zoom" aria-hidden="true"></i></a><a href="https://github.com/joycenerd/P4D" target="_blank"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a>
    </td>
  </tr>

  <tr>
    <td><img src="/images/saliency_guided_masking_teaser.png" width="200"></td>
    <td style="font-size: 17px; line-height: 1.4em;">
      <a href="https://arxiv.org/abs/2309.12757" target="_blank"><strong>Masking Improves Contrastive Self-Supervised Learning for ConvNets, and Saliency Tells You Where</strong></a><br/><strong>Zhi-Yi Chin</strong><sup>&dagger;</sup>, Chieh-Ming Jiang<sup>&dagger;</sup>, Pin-Yu Chen, Ching-Chun Huang, Wei-Chen Chiu<br/><i>In WACV 2024</i><br/><a href="https://github.com/joycenerd/Saliency-Guided-Masking-for-ConvNets" target="_blank"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a><a href="/files/wacv_saliency-guided-masking_poster.pdf" target="_blank"><i class="fa fa-fw fa-columns zoom" aria-hidden="true"></i></a><a href="https://youtu.be/wwUHfZecX7w" target="_blank"><i class="fab fa-fw fa-youtube zoom" aria-hidden="true"></i></a> 
    </td>
  </tr>

  <tr>
    <td><img src="/images/mtmc.png" width="200"></td>
    <td style="font-size: 17px; line-height: 1.4em;">
      <a href="https://openaccess.thecvf.com/content/CVPR2021W/AICity/papers/Li_Multi-Camera_Tracking_by_Candidate_Intersection_Ratio_Tracklet_Matching_CVPRW_2021_paper.pdf" target="_blank"><strong>Multi-Camera Tracking by Candidate Intersection Ratio Tracklet Matching</strong></a><br/>Yun-Lun Li, <strong>Zhi-Yi Chin</strong>, Ming-Ching Chang, Chen-Kuo Chiang.<br/><i>In CVPR Workshop 2021</i>
    </td>
  </tr>
</table>

## Projects

<table>
  <tr>
    <td><img src="/images/3d_aug.png" width="1200"></td>
    <td style="font-size: 17px; line-height: 1.4em;">
      <a href="/projects/3d_augmentation_srn" target="_blank"><strong>3D Point Cloud Data Augmentation via Scene Representation Network</strong></a><br/>Pei-Tse Chiang, Meng-Hsun Tsai, <strong>Zhi-Yi Chin</strong>, Chieh-Ming Jiang.<br/><i>2021 MediaTek Research Project</i><br/>We design a 3D point cloud augmentation based on a novel view synthesis method, scene representation networks, and use PointNet to evaluate our augmented point clouds quality. We replace instance object id with image features from ResNet to apply our method on unseen objects and do interpolation later on. Our method is successful in ModelNet10 and generates the augmented data by intra-class interpolation with ShapeNet in the latent space of SRN encoder.<br/><a href="https://drive.google.com/file/d/1XF3-HgFmed018xAC_xDLn8aQQKn7F5xI/view?usp=sharing" target="_blank"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a><a href="https://github.com/joycenerd/3D_Augmentation" target="_blank"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a><a href="https://drive.google.com/file/d/1dHznm4XqJaUoDaTqxrBWyHligGb5O0d4/view?usp=sharing" target="_blank"><i class="fas fa-fw fa-file-powerpoint zoom" aria-hidden="true"></i></a>
    </td>
  </tr>

  <tr>
    <td><img src="/images/rsna_detect.png" width="1000"></td>
    <td style="font-size: 17px; line-height: 1.4em;">
      <a href="/projects/rsna_detect" target="_blank"><strong>RSNA Pneumonia Detection</strong></a><br/><strong>Zhi-Yi Chin</strong>, Chieh-Ming Jiang.<br/>Final project in <i>Setected Topics in Visual Recognition Using Deep Learning 2021 Fall</i><br/>We design a two stage method for RSNA Pneumonia detection challenge held on Kaggle. We get the best results by using EfficientNet as classification model with 0.2 classification probability threshold when testing, and YOLOR as detection model. At last, we boost the final accuracy 2% by resizing the predicted bounding box to 87.5% of the original size.<br/><a href="https://drive.google.com/file/d/1S0MRRq2Ej19p18ZYs3y1Lb5WDHZN7xLV/view?usp=sharing" target="_blank"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a><a href="https://github.com/joycenerd/rsna-pneumonia-detection" target="_blank"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a><a href="https://drive.google.com/file/d/1iMC_G35EuJ9ObWxtH5yVydpKOANabI_2/view?usp=sharing" target="_blank"><i class="fas fa-fw fa-file-powerpoint zoom" aria-hidden="true"></i></a>
    </td>
  </tr>

  <tr>
    <td><img src="/images/genaug.png" width="500"></td>
    <td style="font-size: 17px; line-height: 1.4em;">
      <a href="/projects/gen_aug" target="_blank"><strong>Generative Models as a Data Augmentation for Classification</strong></a><br/><strong>Zhi-Yi Chin</strong>, Chieh-Ming Jiang.<br/>Final project in <i>Deep Learning and Practice 2021 Summer</i><br/>We investigate image transformation by exploring walks in the latent space of GAN, which is called GAN steer. We conclude that GAN steerability is a better data augmentation technique compare to transformation done in the data space.<br/><a href="https://github.com/joycenerd/genrep_aug" target="_blank"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a><a href="https://youtu.be/y-v_K0sf_lA" target="_blank"><i class="fab fa-fw fa-youtube zoom" aria-hidden="true"></i></a><a href="https://drive.google.com/file/d/1CFHCO4EvMaI3SkhEwThPgjzAdbFhxJF-/view?usp=sharing" target="_blank"><i class="fas fa-fw fa-file-powerpoint zoom" aria-hidden="true"></i></a>
    </td>
  </tr>

  <tr>
    <td><img src="/images/hopper_mse.gif" width="500"></td>
    <td style="font-size: 17px; line-height: 1.4em;">
      <a href="/projects/mpo" target="_blank"><strong>Reimplemenatation Challenge -- Maximum a Posteriori Policy Optimisation</strong></a><br/><strong>Zhi-Yi Chin</strong>,Yi-Hsin Chen, Yu-Hsuan Li, Yu-Jie Chen.<br/>Reimplementation project in <i>Reinforcement Learning 2021 Spring</i><br/>Apart from replicating the algorithm from the paper, we also apply numerical tricks to stabilize the training process. Moreover, We are considering improving the method by modifying the E-step.<br/><a href="/files/Replication__MAXIMUM_A_POSTERIORI_POLICY_OPTIMISATION.pdf" target="_blank"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a><a href="https://github.com/joycenerd/MPO_Reimplementation" target="_blank"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a><a href="https://drive.google.com/file/d/1B-7gZG1zGAiyXOhbjj3MUnvqWFNYPmlD/view?usp=sharing" target="_blank"><i class="fas fa-fw fa-file-powerpoint zoom" aria-hidden="true"></i></a>
    </td>
  </tr>

  <tr>
    <td><img src="/images/lane_dl.png" width="500"></td>
    <td style="font-size: 17px; line-height: 1.4em;">
      <a href="/projects/lane_detection" target="_blank"><strong>Lane Detection</strong></a><br/><strong>Zhi-Yi Chin</strong>, Shao-Yu Weng, Bo-Yu Cheng.<br/>Final project in <i>Computer Vision 2021 Spring</i><br/>We modify two traditional methods and successfully detect more than 2 lanes with accuracy over 70%. We reach high accuracy by apply hourglass network and double hinge loss.<br/><a href="https://drive.google.com/file/d/1LJV8mI4OWEzkpZuscK6ivi0CG5hXPYjl/view?usp=sharing" target="_blank"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a><a href="https://github.com/joycenerd/CV-Lane_Detection" target="_blank"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a><a href="https://youtu.be/9Lgm3DqLSRM" target="_blank"><i class="fab fa-fw fa-youtube zoom" aria-hidden="true"></i></a><a href="https://drive.google.com/file/d/1cSbJufF0toUBbvIdfA6lWSeHp_4uOVgO/view?usp=sharing" target="_blank"><i class="fas fa-fw fa-file-powerpoint zoom" aria-hidden="true"></i></a>
    </td>
  </tr>

  <tr>
    <td><img src="/images/mango_2.png" width="500"></td>
    <td style="font-size: 17px; line-height: 1.4em;">
      <a href="/projects/mango" target="_blank"><strong>Mango Classification</strong></a><br/><strong>Zhi-Yi Chin</strong>, Tzu-Cheng Lin, Kung-Hao Chang, Yu-Chang Chen.<br/>Final project in <i>Machine Learning 2020 Spring</i><br/>Achieve accuracy 82.31% on the testing data and rank 8 in the public board in AICUP Mango Image Recognition Challenge: Grade Classification and Defective Classification.<br/><a href="https://drive.google.com/file/d/1vvNUUzQjSnW9sH7fi-XBtS0wj-JHNU6d/view?usp=sharing" target="_blank"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a><a href="https://github.com/joycenerd/AICUP_MangoClassification" target="_blank"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a>
    </td>
  </tr>

  <tr>
    <td><img src="/images/warp_2.png" width="500"></td>
    <td style="font-size: 17px; line-height: 1.4em;">
      <a href="/projects/morph_warp" target="_blank"><strong>Face Morphing and Warping</strong></a><br/><strong>Zhi-Yi Chin</strong>.<br/>Final project in <i>Introduction to Multimedia Technology in Fall 2019</i><br/>Face swapping from my face to another person's face smoothly without ghost effect by morphing and warping technique.<br/><a href="https://github.com/joycenerd/MT_2019/tree/master/final_project" target="_blank"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a><a href="https://youtu.be/y_3ZicAO42o" target="_blank"><i class="fab fa-fw fa-youtube zoom" aria-hidden="true"></i></a>
    </td>
  </tr>

  <tr>
    <td><img src="/images/cal_helper.png" width="500"></td>
    <td style="font-size: 17px; line-height: 1.4em;">
      <a href="/projects/calendar_helper" target="_blank"><strong>Calendar Helper</strong></a><br/><strong>Zhi-Yi Chin</strong>, Mi Li, Jhong-Yu Huang.<br/>Google CodeU project 2019<br/>It is a multifunctional platform for to-do lists and calendars. Its highlight is that we have added a tagging system to calendar events/tasks.<br/><a href="https://github.com/joycenerd/codeu-calendar_helper" target="_blank"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a>
    </td>
  </tr>
</table>

## Honors

* **Dean's list (6 times)**, Computer Science and Information Engineering Dept. at CCU, Fall '17, Spring '18, Fall '18, Spring '19, Fall '19, Spring '20
* **College Student Research Scholarship**, get NT$ 48,000 from Ministry of Science and Technology, 2020
* **Google Student Travel Scholarship**, scholarship to attend Grace Hopper Celebration, 2019

## Miscellaneous

### Books I enjoy

* **Atomic Habits** by James Clear
* **Make Time** by Jake Knapp and John Zeratsky
* **Show Your Work** by Austin Kleon

### TV shows I enjoy

* Grey's Anatomy
* Black Dog: Being A Teacher
* Start-Up
* Live On
* Hospital Playlist




