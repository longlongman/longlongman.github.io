---
layout: archive
permalink: /
title: "About me"
excerpt:
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

About me
======


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
