---
layout: project
title: Targetting at-risk students in Computer Science
collaborators: Alan Smeaton
image: /images/targetting_diagram.png
excerpt:
    We present a system for articulated human tracking and show that *unscented Kalman filtering* (UKF) allows for less likelihood evaluations compared to particle filtering (PF). Moreover, we achieve a smoother tracking with lower errors using UKF rather than PF.
---

## Abstract
This paper presents a new approach to automatically detecting lower-performing or “at-risk” students on computer programming modules in an undergraduate University degree course. Using historical data from previous student cohorts we built a predictive model using logged interactions between students and online resources, as well as students’ progress in programming laboratory work. Predictions were calculated each week during a 12-week semester. Course lecturers received student lists ranked by their probability of failing the next computer-based laboratory exam. At-risk students were targeted and offered assistance during laboratory sessions by the lecturer and laboratory tutors. When we group students into two cohorts depending on whether they failed or passed their first laboratory exam, the average margin of improvement on the second laboratory exam between the higher and lower-performing students was four times higher when our predictions were run and subsequent laboratory support targeted at these students, compared to students from the year our model was trained on.

## Publications
* {% reference azcona2017targeting %} {% cite_details azcona2017targeting %} / [PDF]({{ site.pubs_path }}/azcona2017targeting.pdf)
* More will be added soon!

## Further details

<img class="post-image-bottom" src="{{ site.baseurl }}/images/targetting_cao.png" />

<img class="post-image-bottom" src="{{ site.baseurl }}/images/targetting_map.png" />

<img class="post-image-bottom" src="{{ site.baseurl }}/images/targetting_einstein.png" />

<img class="post-image-bottom" src="{{ site.baseurl }}/images/targetting_testcase.png" />

<img class="post-image-bottom" src="{{ site.baseurl }}/images/targetting_diagram.png" />

<img class="post-image-bottom" src="{{ site.baseurl }}/images/targetting_notification.png" />

## Software
The code is will be available on my [Github][github] soon. 

[github]: http://github.com/dazcona