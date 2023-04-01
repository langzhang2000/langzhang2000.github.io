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
* B.S. (with honor) in Mathematics and Applied Mathematics, Northeast Forestry University, China, 2012-2016 
* Ph.D in Computer and Information Science, Temple University, US, 2017-2020 (transferred to VT at 2020 Fall)
* Ph.D in Computer Science, Virginia Tech, US, 2020 - now 

Research experience
======
* 2017 - now: Research Project, Age-of-Information Analysis and Scheduling in Information-Update Systems
  * Temple University & Virginia Tech, US, advised by [Dr.Bo Ji](https://people.cs.vt.edu/boji/).
  * The Age-of-Information (AoI) is a fundamentally novel performance metric recently proposed for measuring the freshness of information in information-update systems, which is shown to be significantly different to existing timeliness metrics such as delay and throughput. 
  * Through this project, we try to analyze AoI in various real-time systems and networks and propose AoI-efficient scheduling policies to improve the information freshness of those systems.

* 2016 - 2017: Research Project, Downlink Beamforming Optimization in Massive MIMO with Stochastic Approximation
  * Southern University of Science and Technology, China, advised by [Dr.Rui Wang](https://eee.sustc.edu.cn/p/wangrui/).
  * Massive MIMO equips cellular base stations with lots of antennas and has been shown to potentially allow for orders of magnitude improvement in spectral and energy efficiency.
  * Our gaol is to design an innovative algorithm for downlink beamforming optimization in Massive MIMO using the stochastic approximation technologies.

* 2014 - 2015: Undergraduate Research Project, Delay Differential Equations in Forestry Ecology
  * Northeast Forestry University, China, advised by Prof.Wenlong Wang.
  * Study the fundamental theories on delay differential equations and forestry ecology.
  * Combined the statistical methods and mathematical software (such as MATLAB), the stability of the future forest is analyzed, and suggestions are provided to make the forest system stable.
  
Skills
======
* Programming Languages
  * Java
  * Python
* Analysis of Networking and Algorithms

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
