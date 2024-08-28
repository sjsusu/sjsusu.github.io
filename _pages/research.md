---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}
Welcome to my research page! \
My interests lie in Numerical Analysis and Computational Mathematics.

<!-- Undergraduate Research -->
{% for post in site.undergrad_research %}
  {% include archive-single.html %}
{% endfor %}