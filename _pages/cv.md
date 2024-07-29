---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education
======
* Ph.D in Physics: Quantum Information, Quantum Information Group @ Autonomous University of Barcelona, 2022-2026 (expected)
* M.Sc. in Quantum Science and Technology, Basque Country University, 2020-2021
* B.Sc. in Physics, Autonomous University of Barcelona, 2015-2020
* B.Sc. in Chemistry, Autonomous University of Barcelona, 2015-2020

Research experience
======
  <ul>{% for post in site.experience reversed %}
    {% include archive-single-experience-cv.html %}
  {% endfor %}</ul>

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
 <ul>{% for post in site.teaching reversed %}
    {% include archive-single-teaching-cv.html %}
  {% endfor %}</ul>

