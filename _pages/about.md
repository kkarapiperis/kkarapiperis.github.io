---
permalink: /
title: #"About me"
excerpt: "About me (excerpt)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Postdoctoral Scholar and Lecturer at the [Mechanics and Materials Laboratory](https://mm.ethz.ch/) at ETH Zürich. My research focuses on data-driven multiscale modeling and design of materials. I received my PhD in Applied Mechanics from Caltech at 2020. I also hold a Minor in Applied and Computational Mathematics from Caltech and MSc's in Civil Engineering from UC Davis and the National Technical University of Athens.

<!-- Research group: [Complex Systems Modeling](https://http://cosymo.caltech.edu/) -->

## News ##

{% for post in site.posts %}
  {% include archive-single-talk.html %}
{% endfor %}
