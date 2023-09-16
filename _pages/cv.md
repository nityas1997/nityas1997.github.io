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
* Bachelor of Engineering in Electrical and Computer Engineering, RV College of Engineering, 2019
* PhD candidate in Electrical and Computer Engineering, Rutgers University, 2019-present

Research Projects
======
* Privacy Leakage in Discrete-Time Updating Systems
  * Studied the tradeoff between privacy and timeliness in discrete time- time systems where a source generates time-stamped packet updates as a Bernoulii process.
  * Used the maximal leakage metric to quantify privacy loss of the source and the age of information metric to measure timeliness of updates  at the destination.
  * Analyzed three policies on how the server, which receives time-stamped packets from the source must submit packets to an interested recipient/monitor.
  * Found optimal server policies (within a given class) to manage age-leakage tradeoff for Bernoulli arrivals.

* REALTIME: Resilient Edge- Cloud Autonomous Learning with Timely Inferences
  * The project is about developing frameworks for real-time operation of ML based applications that must be resilient to data, user and system changes.
  * Currently working on creating privacy metrics for real time operation of edge-assisted ML systems.
  
Skills
======
* Python (Pandas, Pytorch, NumPy, Scikit-learn), Matlab, C/C++
* Latex, Microsoft Office

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
    
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

