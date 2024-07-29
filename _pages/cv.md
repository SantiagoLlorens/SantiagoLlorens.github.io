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
* Ph.D in Physics: Quantum Information, Quantum Information Group @ Autonomous University of Barcelona, 2022-2026 (expected)
* M.Sc. in Quantum Science and Technology, Basque Country University, 2020-2021
* B.Sc. in Physics, Autonomous University of Barcelona, 2015-2020
* B.Sc. in Chemistry, Autonomous University of Barcelona, 2015-2020

Research experience
======
  <ul>{% for post in site.experience reversed %}
    {% include archive-single-experience-cv.html %}
  {% endfor %}</ul>


[comment]:Research experience
[comment]:======
[comment]:* 2022-2026 (expected) Ph.D Student
[comment]:  * Quantum Information Group (GIQ), Autonomous University of Barcelona
[comment]:  * New techniques for verification and identification of quantum states and processes

[comment]:* 2020-2021 M.Sc. Thesis Student
[comment]:  * Physics Department, Basque Country University
[comment]:  * Bloch Representation on Finite-Dimensional Composite Systems

[comment]:* 2019-2020 B.Sc. Thesis Student
[comment]:  * Quantum Information Group (GIQ), Autonomous University of Barcelona
[comment]:  * Implementation of SPRT in quantum state discrimination

[comment]:* 2019-2020: B.Sc. Thesis Student
[comment]:  * Physical Chemistry Department, University of Seville
[comment]:  * Theoretical insight into the PUREX method mechanism

[comment]:* July 2019: Visiting Student
[comment]:  * Physical Chemistry Department, University of Seville
[comment]:  * _ab initio_ simulations on uranyl, neptunyl and plutonyl extractions in the PUREX method

[comment]:* July 2018: Visiting Students
[comment]:  * Physical Chemistry Department, University of Seville
[comment]:  * _ab initio_ simulations on aqueous electrolyte solutions
  
[comment]: <> Skills
[comment]: <> ======
[comment]: <> * Skill 1
[comment]: <> * Skill 2
[comment]: <>   * Sub-skill 2.1
[comment]: <>   * Sub-skill 2.2
[comment]: <>   * Sub-skill 2.3
[comment]: <> * Skill 3

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

