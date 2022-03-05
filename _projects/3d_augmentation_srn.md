---
title: 3D Point Cloud Data Augmentation via Scene Representation Network
collection: projects
type: "Research Project"
permalink: /projects/3d_augmentation_srn
venue: "MediaTek"
date: 2022-02-25
github: "https://github.com/joycenerd/3D_Augmentation"
slide: "https://drive.google.com/file/d/1dHznm4XqJaUoDaTqxrBWyHligGb5O0d4/view?usp=sharing"
paperurl: "https://drive.google.com/file/d/1XF3-HgFmed018xAC_xDLn8aQQKn7F5xI/view?usp=sharing"
---

Try novel view synthesis method to do point cloud data augmentation.
<img src="/images/3d_aug_result.png">

We design a 3D point cloud augmentation based on a novel view synthesis method, [SRN](https://arxiv.org/pdf/1906.01618.pdf). The 3D point cloud is a set of data points in 3D space, consisting of coordinates in world space and RGB color information. However, the precision is limited if there are insufficient points to describe the objects. Moreover, the amount of point cloud training samples is also limited, leading to the poor diversity of data. This motivates us to design a data augmentation method for the point cloud. As our base model, given extrinsic and intrinsic matrix, the SRN model can estimate the world coordinate and get the corresponding depth and RGB color information, which can easily be transferred to point cloud form. After the SRN model is trained, we can render new images of unseen views by changing the extrinsic matrix and consequently realize the point cloud augmentation. To verify whether the augmented point cloud is good enough to describe the 3D objects, we use [PointNet](https://arxiv.org/pdf/1612.00593.pdf) as our evaluation model to evaluate the quality of the augmentation.

In order to apply our method on unseen objects and do interpolation with other objects, we have replace the instance object id embedding with images features from ResNet encoder. Also, for intra-class and inter-class interpolation, we mix different objects in the latent space to generate augmented objects. This is a way of increasing diversity of our data. 

We have done many experiments, and our method is successful in ModelNet10. But we have observe the limitation of novel view synthesis method on non-texture data when we use ModelNet40. To make up the color information that non-texture data is lack of, there must be extra information be included when training. This may be an interesting future work.

**More information of our implementation:** \
Report: <a href="https://drive.google.com/file/d/1XF3-HgFmed018xAC_xDLn8aQQKn7F5xI/view?usp=sharing" target="_blank"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> \
Code: <a href="https://github.com/joycenerd/3D_Augmentation" target="_blank"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a> \
Slides: <a href="https://drive.google.com/file/d/1dHznm4XqJaUoDaTqxrBWyHligGb5O0d4/view?usp=sharing" target="_blank"><i class="fas fa-fw fa-file-powerpoint zoom" aria-hidden="true"></i></a>