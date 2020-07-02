---
permalink: /
title: #"About me"
excerpt: "About me (excerpt)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD candidate in the [Mechanical and Civil Engineering](https://http://mce.caltech.edu/) Department at Caltech. My research focuses on data-driven, multiscale and complex-systems modeling of granular materials. Previously I have studied stochastic inelasticity of materials, in UC Davis, and reduced-order modeling of foundation systems, in NTUA, Greece.

<!-- Research group: [Complex Systems Modeling](https://http://cosymo.caltech.edu/) -->

## News ##

{% for post in site.posts %}
  {% include archive-single-talk.html %}
{% endfor %}
