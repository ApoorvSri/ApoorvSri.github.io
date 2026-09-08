---
layout: page
title: research
permalink: /research/
description: The projects I have spent most of my time on.
nav: true
nav_order: 1
display_categories: [research]
horizontal: false
---

<div class="projects">
{% assign sorted_projects = site.projects | where: "category", "research" | sort: "importance" %}
<div class="row row-cols-1 row-cols-md-2">
{% for project in sorted_projects %}
  {% include projects.liquid %}
{% endfor %}
</div>
</div>
