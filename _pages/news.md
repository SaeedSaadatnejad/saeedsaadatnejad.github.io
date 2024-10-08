---
layout: page
title: news
permalink: /news/
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
      {% include news.html %}
  </div>
  <br><br>
  <div class="container">
    {% twitter https://twitter.com/ssaadatnejad maxwidth=500 limit=3 %}
  </div>
</div>