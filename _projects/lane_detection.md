---
title: Lane Detection
collection: projects
type: "Final Project"
permalink: /projects/lane_detect
venue: "National Yang Ming Chiao Tung University"
date: 2021-06-28
github: "https://github.com/joycenerd/CV-Lane_Detection"
paperurl: "https://drive.google.com/file/d/1LJV8mI4OWEzkpZuscK6ivi0CG5hXPYjl/view?usp=sharing"
slide: "https://drive.google.com/file/d/1cSbJufF0toUBbvIdfA6lWSeHp_4uOVgO/view?usp=sharing"
youtube: "https://youtu.be/9Lgm3DqLSRM"
---

Lane detection using both deep learning method and traditonal computer vision method.
<img src="/images/lane_detection_res.png">

Lane detection, as the name suggests, is detecting lanes on the road. Currently, lane detection has been used in lane departure warning systems (LDWS). After learning many topics and techniques in computer vision this semester, we want to make something related to some of the topics and compare the results of deep learning methods and the traditional method. 

For the traditional method, we find two different pipelines that can detect lane lines with acceptable accuracy. The main contribution of our traditional method is that we successfully detect more than 2 lane lines, which haven’t been tried using traditional CV methods before, to the best of our knowledge. Our algorithms try to detect 4 lane lines in all images, and achieve about 70% accuracy on Tusimple dataset.

For the deep learning method, we apply two hourglass network with lane loss and double hinge loss for lane detection. This method showed 97% accuracy on the TuSimple dataset. 

Overall, the contributions of our work are as follows:
- We modify two traditional methods and successfully detect more than 2 lanes with accuracy over 70%.
- We reach high accuracy by apply hourglass network and double hinge loss.
- Compare the accuracy and show the results between three methods.

**More information of our implementation:** \
Report: <a href="https://drive.google.com/file/d/1LJV8mI4OWEzkpZuscK6ivi0CG5hXPYjl/view?usp=sharing" target="_blank"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> \
Code: <a href="https://github.com/joycenerd/CV-Lane_Detection" target="_blank"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a> \
Video: <a href="https://youtu.be/9Lgm3DqLSRM" target="_blank"><i class="fab fa-fw fa-youtube zoom" aria-hidden="true"></i></a> \
Slides: <a href="https://drive.google.com/file/d/1cSbJufF0toUBbvIdfA6lWSeHp_4uOVgO/view?usp=sharing" target="_blank"><i class="fas fa-fw fa-file-powerpoint zoom" aria-hidden="true"></i></a>
