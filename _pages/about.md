---
permalink: /
title: #"About me"
excerpt: "About me (excerpt)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an Assistant Professor and Director of the [Data-Driven Mechanics Lab](https://www.epfl.ch/labs/lmd/) at EPFL. Previously I have have been a Postdoctoral Scholar and Lecturer at the Mechanics and Materials Laboratory at ETH Zürich. My research focuses on data-driven multiscale modeling and design of materials, with special interest in granular materials, soft materials, and structural materials. I received my PhD in Applied Mechanics from Caltech at 2020. I also hold a Minor in Applied and Computational Mathematics from Caltech and MSc's in Civil Engineering from UC Davis and the National Technical University of Athens.

<!-- Research group: [Complex Systems Modeling](https://http://cosymo.caltech.edu/) -->

## News ##

{% for post in site.posts %}
  {% include archive-single-talk.html %}
{% endfor %}
