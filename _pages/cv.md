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
* Ph.D. in Computer Science, Linköping University, 2025 (expected)
* M.Sc. in Applied Physics and Electrical Engineering, Linköping University, 2020
  * Track: Theory, modeling, and computations
  * Thesis title: Graph neural networks for prediction of formation energies of crystals

Work experience
======
* Summer 2019: Machine learning intern
  * Ericsson Research, Linköping
  * Data collection and analysis
  
Skills
======
* Machine learning
  * Deep learning
  * Graph neural networks
  * Diffusion models
  * Sequential Monte Carlo
* Python programming
  * Implementations of machine learning methods

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Reviewer AISTATS 2024
* Reviewer AISTATS 2025
