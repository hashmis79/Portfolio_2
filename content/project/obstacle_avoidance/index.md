---
date: "2024-07-28"
# external_link: https://www.youtube.com/watch?v=41vC9Gt_iTY
tags:
- Obstacle-Avoidance
- Stereovision
- Image-Processing
title: Obstacle detection and collision avoidance for multi-rotor UAV
url_video: https://www.youtube.com/watch?v=41vC9Gt_iTY
---
Drones are actively used in precision agriculture with one of its major applications of spraying pesticides, herbicides, fertilizers, etc. in the agricultural field. The aim of this project is to develop a reliable sense and avoid technology to make UAV-based spraying completely autonomous. The major challenge in achieving autonomy is the requirement of flying low in an agricultural environment with lots of obstacles like trees, poles, cables, etc.
  As an engineer at TIH, IIT-Bombay, I worked on the development of a robust obstacle detection and avoidance suite capable of navigating through common obstacles in the agricultural field. The figure below displays the functioning of our sense and avoidance technology.
<div class="figure">
<img src="{{< blogdown/postref >}}index.en_files/figure-html/sna_gif.gif" alt="slide_2" width="672" />
<p class="caption"><span id="fig:pie"></span></p>
</div>
In collaboration with General Aeronautics (GA), Bangalore, we tested our technology on different scenarios.
* Trees of different shapes and sizes
<div class="figure">
<img src="{{< blogdown/postref >}}index.en_files/figure-html/slide_2.gif" alt="slide_2" width="672" />
<p class="caption"><span id="fig:pie"></span></p>
</div>
* Detection and avoidance at different heights,
<div class="figure">
<img src="{{< blogdown/postref >}}index.en_files/figure-html/slide_3.gif" alt="slide_3" width="672" />
<p class="caption"><span id="fig:pie"></span></p>
</div>
* Detection and avoidance for multiple obstacles.
<div class="figure">
<img src="{{< blogdown/postref >}}index.en_files/figure-html/slide_4.gif" alt="A fancy pie chart." width="672" />
<p class="caption"><span id="fig:pie"></span></p>
</div>
We have successfully tested our implementation in the presence of dust and high winds. Currently, we are working towards modifying the avoidance algorithm to maximize spraying in the marked area in the agricultural field.

<!--more-->
