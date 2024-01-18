---
layout: page
permalink: /research/
title: research
description: Publications, working papers, ongoing research, and policy reports
years: [2025,2024,2023,2022,2021,2020,2019,2018]
type: [WP soon, in progress]
nav: true
publications: false
---


### ongoing research
<div class="publications">

{% for y in page.type %}
  <!-- <h2 class="year">{{y}}</h2> -->
  {% bibliography -f ongoing -q @*[abbr={{y}}]* %}
{% endfor %}

</div>

</div>