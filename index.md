---
title: DIGH 401
layout: default-vertical

categories:
- general
- site

tags: general site home
published: true
summary: Intro to Computing, Fall 2015
---

Welcome to the course website for DIGH 401, *Intro to Computing*. 

This course is offered by the [Center for Textual Studies and Digital Humanities](http://www.luc.edu/ctsdh/) and the [Department of Computer Science](http://www.luc.edu/cs/) at [Loyola University Chicago](http://www.luc.edu).

***

#### Recent Updates
{% for post in site.posts limit: 5 %}
* {{ post.date | date_to_string }} | [{{ post.title }}]({{ post.url }})

  {{ post.summary }}
{% endfor %}




