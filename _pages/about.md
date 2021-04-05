---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD student at the [University of Tübingen] and the [Max Planck Research School for Intelligent Systems (IMPRS-IS)](https://imprs.is.mpg.de/), working in the lab of [Matthias Bethge](http://bethgelab.org/) under the supervision of [Wieland Brendel](https://scholar.google.de/citations?user=v-JL-hsAAAAJ). I've completed my Bachelors and Masters from the [University of Göttingen](https://www.uni-goettingen.de/en/1.html), and have spent time at Volkswagen and BMW.

I started doing research on object detection and segmentation. In the recent past I have primarily worked on understanding failure cases of machine learning models in computer vision tasks through the lense of adversarial perturbations and common corruptions. This lead me to my next goal: aligning the decision process of machines with that of humans by recreating the natural learning process and inducing priors.

Current research interests: *self-supervised learning, adversarial robustness, disentanglement*

Latest Publications
======
  {% assign reversed_publications = site.items | reverse %}
  <ul>{% for post in reversed_publications limit:3 %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>