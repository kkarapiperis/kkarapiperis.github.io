---
permalink: /
title: #"About me"
excerpt: "About me (excerpt)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD candidate in the [Mechanical and Civil Engineering](https://http://mce.caltech.edu/) Department at Caltech. My research focuses on data-driven, multiscale and complex-systems modeling of granular materials.

<!-- Research group: [Complex Systems Modeling](https://http://cosymo.caltech.edu/) -->

## News ##

{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}
