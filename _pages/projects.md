---
layout: page
title: projects
permalink: /projects/
description: 
nav: false
nav_order: 2
# display_categories: [work, fun]
horizontal: false
---

<!-- pages/projects.md -->
<div class="projects">
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.projects | sort: "importance" -%}
  <!-- Generate cards for each project -->
  <div class="container">
      {% include projects.html %}
  </div>
  <br><br>
</div>