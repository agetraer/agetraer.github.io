---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Alexander Getraer
------

Education 
------
* <b>Ph.D. Student</b>, Earth Sciences, Dartmouth College, 2022–present
  * Advisors: [Marisa C. Palucis](https://www.marisapalucis.com/), [Justin V. Strauss](https://sites.dartmouth.edu/strausslab/)
* <b>B.A.</b>, Geosciences, Princeton University, 2019
  * <b>Thesis:</b> [<i>Tributary slopes record regional climate and constrain branching angles in U.S. river networks</i>](http://arks.princeton.edu/ark:/88435/dsp01m900nx25n)
  * <b>Advisor:</b> [Adam C. Maloof](https://maloof.princeton.edu/)

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
