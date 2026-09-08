---
layout: page
title: other projects
permalink: /other-projects/
description: Shorter projects and things I worked on as a student.
nav: true
nav_order: 3
horizontal: false
---

<div class="projects">
{% assign sorted_projects = site.projects | where: "category", "other" | sort: "importance" %}
<div class="row row-cols-1 row-cols-md-2">
{% for project in sorted_projects %}
  {% include projects.liquid %}
{% endfor %}
</div>
</div>
