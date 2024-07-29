---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

Below you will find my teaching history. <!--as well as syllabi for the courses.-->

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single-teaching-cv.html %}
{% endfor %}