---
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

Currently I am a Ph.D. student of the [AI school](https://ai.nju.edu.cn/main.htm) in [Nanjing University](https://www.nju.edu.cn/main.htm) and a member of [NJUNLP Group](http://nlp.nju.edu.cn/homepage). Before that, I received the B.Sc. degree in the [school of computer science and technology](http://www.cs.xjtu.edu.cn) in [Xi'an Jiaotong University](http://www.xjtu.edu.cn).

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
