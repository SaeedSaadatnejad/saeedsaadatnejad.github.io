---
layout: page
permalink: /publications/
title: publications
description: # publications by categories in reversed chronological order. generated by jekyll-scholar.
years: [2025, 2024, 2023, 2022, 2021, 2020, 2019] #[1967, 1956, 1950, 1935, 1905]
nav: true
nav_order: 1
---
For the full list, please refer to my [scholar](https://scholar.google.com/citations?user=PBdhgFYAAAAJ&hl=en).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
