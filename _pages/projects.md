---
layout: page
title: news
permalink: /projects/
description: 
nav: true
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
  <div class="container">
    {% twitter https://twitter.com/ssaadatnejad maxwidth=500 limit=3 %}
  </div>
</div>