---
layout: page
title: Research work
description: Research work of Van Khoa LE
permalink: /research/
---

Below is a list of my research publications. You might also want to take a look at my [Google Scholar](https://scholar.google.com/citations?user=TbNCzO8AAAAJ&hl=en) profiles in the links provided:


## Neuromorphic

I had my journey doing research about Neuromorphic domain when I worked at IMRA Europe. At first we played with an event camera, which is a camera that capture every movement in it's FOV (which also means it can not see you if you stand still). The output of this camera is not frame as normal camera but an asynchronous stream of _events_ (spatial-temporal signal). From the output of this camera, we can think of many approaches to recognize patterns such as recreate frame by cumulate _events_, or try to recognize directly this stream of events. 

I was interested more on the latter approach and started to do research on Spiking Neural Network (SNN), the third generation of neural network (after deep learning that we know and other network from 1950s). The output of this research was a demo of hand gesture recognition using event camera and SNN. I also made a meetup at Sophia Antipolis for an introduction of SNN. 

Link to the [paper](https://aircconline.com/csit/abstract/v10n1/csit100105.html)

### PhD Thesis

This thesis takes a role in the VIRTUALIS project , partner with companies like Thalès and other PMEs. The objective of this project is to create an intelligent surveillance system. This thesis contributed 2 methods to detect abnormal events in the building. The data that we used to analyze were capture from the building of Thales in Paris Palaiseau, which were trajectories of people inside the building and other signals (badge, infrared sensor). The first method was a statistical classifier based on multiple metrics such as stay duration, moving speed, etc. The second method was a kernel method to map the trajectories into a high dimentional space, and apply One Class SVM classifier to detect the anomalies. I published two articles based on these two approaches in two different conferences, and got the best presentation award in the ICDSP 2018 conference.

### Master Thesis

With the advices of my professor, we developed the kernel path algorithm to quickly train a One Class SVM model using another pretrained model. An article was published with this algorithm at the ICMLA 2015 conference.

