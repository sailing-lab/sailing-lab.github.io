---
layout: page
permalink: /publications/
title: publications
description: <a href="http://www.cs.cmu.edu/~epxing/publications-2021.html">Link to Publications</a>
years: [2021, 2020]
nav: true
---

<div class="publications">
<h2>Jump to: <a href="#publications">publications</a>, <a href="#dissertations">dissertations</a>.</h2>

<h2 id="publications">publications</h2>
{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

<h2 class="year" id="dissertations">theses</h2>
{% bibliography -f dissertations %}

</div>
