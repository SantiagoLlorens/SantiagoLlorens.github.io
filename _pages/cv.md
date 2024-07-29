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
* Ph.D in Physics: Quantum Information, Quantum Information Group @ Autonomous University of Barcelona, 2022-2026 (expected)
* M.Sc. in Quantum Science and Technology, Basque Country University, 2020-2021
* B.Sc. in Physics, Autonomous University of Barcelona, 2015-2020
* B.Sc. in Chemistry, Autonomous University of Barcelona, 2015-2020

<div class="text-center" style="text-align: center;">
  <div class="row" style="display: flex; justify-content: center;">
    <a href="https://www.uab.cat/web/universitat-autonoma-de-barcelona-1345467954774.html" target="_blank" style="display: block; width: 210px; height: 100px; border: 2px solid rgba(0, 0, 0, 0.5); border-radius: 50%; overflow: hidden; display: flex; align-items: center; justify-content: center; margin-right: 60px;">
      <img src="https://santiagollorens.github.io/images/UAB_logo.jpg" 
           alt="UAB Logo" 
           style="width: 120%; height: 120%; object-fit: cover; transform: scale(0.8);">
    </a>
    <a href="https://www.ehu.eus/en/en-home" target="_blank" style="display: block; width: 210px; height: 100px; border: 2px solid rgba(0, 0, 0, 0.5); border-radius: 50%; overflow: hidden; display: flex; align-items: center; justify-content: center;">
      <img src="https://santiagollorens.github.io/images/UPV_logo.jpg" 
           alt="UPV Logo" 
           style="width: 100%; height: 100%; object-fit: cover; transform: scale(0.8);">
    </a>
  </div>
</div>
## Research experience
  <ul>{% for post in site.experience reversed %}
    {% include archive-single-experience-cv.html %}
  {% endfor %}</ul>

## Publications
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Talks
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
## Teaching
 <ul>{% for post in site.teaching reversed %}
    {% include archive-single-teaching-cv.html %}
  {% endfor %}</ul>

