---
layout: page
permalink: /publications/
title: Publications
description: 
years:  [2025, 2024, 2023, 2022, 2018 and Before (Undergrad Research)]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

<p>
    <mark>Summary: five first-author papers published in top-tier security (ACM CCS’2022 * 2 and NDSS’2025 * 2) and software engineering  (ACM FSE’2024) conferences.</mark>
</p>


 <!-- <p> <small> * Equal contribution.</small><br>
 <!-- <small> Papers before 2019 are my undergraduate research works. </small><br> -->
 <!-- the end is this other phrase.. -->
 <!-- </p> --> 

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>