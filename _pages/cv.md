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
------
Ph.D. student in Earth Sciences, Dartmouth College, 2022–present 
B.A. in Geosciences, Princeton University, 2019

Publications
------
  <ol reversed>
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ol>
  
<!-- Talks
------
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
------
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
