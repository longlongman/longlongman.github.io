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

[中文简历](../files/cv_zh.pdf)

Currently I am a Ph.D. student of the [AI school](https://ai.nju.edu.cn/main.htm) in [Nanjing University](https://www.nju.edu.cn/main.htm) and a member of [NJUNLP Group](http://nlp.nju.edu.cn/homepage). Before that, I received the B.Sc. degree from the [school of computer science and technology](http://www.cs.xjtu.edu.cn) in [Xi'an Jiaotong University](http://www.xjtu.edu.cn).

My research focuses on the exploration and development of generative and pre-trained models, aiming to deeply understand their wide applications in the scientific domain. This includes utilizing generative models for targeted drug design, innovative protein structure design, and the construction of pre-trained models for biological structures.

Education
======
* Ph.D. student, Nanjing University, 2019 - now
* B.S., Xi'an Jiaotong University, 2015 - 2019

Internships
======
* Institute for Al Industry Research (AIR), 2023 - now
* ByteDance AI Lab, 2021 - 2023

Publications
======
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>