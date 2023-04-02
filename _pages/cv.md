---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Data Science and Big Data Technology, Chongqing University, China, 2019-2023 
* Ph.D in Computer Science, Virginia Tech, US, 2023 - now 

Research experience
======
* 2021.10 - 2023.08: Undergraduate Research Project, Belief Divergence Theory and Its Application in Multisource Information Fusion
  * Chongqing University, China, advised by [Prof. Xiao](http://www.cse.cqu.edu.cn/info/2095/5902.htm).
  * Combined convolutional neural networks and evidence theory together with multi-head self-attention mechanisms.
  * Explored the application of divergence in evidence theory to medical problems.
  
Skills
======
* Programming Languages
  * Python, Matlab
* Research Tool
  * Origin, Echarts
* Data Analysis and Machine Learning Algorithm

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
