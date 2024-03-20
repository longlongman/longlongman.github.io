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
* Ph.D. student, Nanjing University, 2019 - now
* B.S., Xi'an Jiaotong University, 2015 - 2019

Internship
======
* Institute for Al Industry Research (AIR), 2023 - now
* ByteDance AI Lab, 2021 - 2023

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
