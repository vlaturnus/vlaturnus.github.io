---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Working Paper
======
  <ul>{% for post in site.posts reversed %}
    {% include archive-single-posts-cv.html  %}
  {% endfor %}</ul>


Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
