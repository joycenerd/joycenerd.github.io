---
title: Face Morphing and Warpinng
collection: projects
type: "Final Project"
permalink: /projects/morph_warp
venue: "National Chung Cheng University"
date: 2020-01-13
github: "https://github.com/joycenerd/MT_2019/tree/master/final_project"
youtube: "https://youtu.be/y_3ZicAO42o"
---

Swapping face gradually using image morphing and warping technique.
<img src="/images/warp.png">

This project is the final work of the "Introduction to Multimedia Technology" class in the junior year. In order to avoid ghost effect when overlapping different faces, we need to make proper deformations. I will record a video with my head moving up and down, left and right, and another classmate will also. In the pre-processing part of the data, I want to cut the overlapping part of the two videos into a frame. And mark the same number of feature points on the faces of two people in each frame. Then write a program to form all the feature points into equal triangles. I use the triangles to affine the triangles. Because the superposition is to transform my face into the face of another classmate, the feature points interpolated by the affine transformation change over time. The points interpolated in the first few frames that are superimposed will be closer to my triangle, and the points interpolated in the later frames will be more biased towards the triangle of another classmate. Each triangle piece will form a transformation matrix, and the points on the same triangle piece will go through the transformation matrix to the interpolated point, and the colors of the two faces will be superimposed. The color and the feature points are superimposed and change over time. Finally, these generated superimposed frames can be combined into a video.

Here is the code: <a href="https://github.com/joycenerd/MT_2019/tree/master/final_project" target="_blank"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a>