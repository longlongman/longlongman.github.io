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

Currently I am a Ph.D. student of the [AI school](https://ai.nju.edu.cn/main.htm) in [Nanjing University](https://www.nju.edu.cn/main.htm) and a member of [NJUNLP Group](http://nlp.nju.edu.cn/homepage). Before that, I received the B.Sc. degree from the [school of computer science and technology](http://www.cs.xjtu.edu.cn) in [Xi'an Jiaotong University](http://www.xjtu.edu.cn).

My research focuses on the exploration and development of generative and pre-trained models, aiming to deeply understand their wide applications in the scientific domain. This includes utilizing generative models for targeted drug design, innovative protein structure design, and the construction of pre-trained models for biological structures.

<!-- Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
