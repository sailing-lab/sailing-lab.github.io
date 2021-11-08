---
layout: page
permalink: /publications/
title: publications
description: Please see <a href="http://www.cs.cmu.edu/~epxing/publications-2021.html"><u>here</u></a> for publications before 2016.
years: [2021, 2020, 2019]
nav: true
---

<div class="publications">
<h2>Jump to: <a href="#publications">publications</a>, <a href="#dissertations">dissertations</a>.</h2>

<h1 id="publications">publications</h1>
{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

<h1 class="year" id="dissertations">theses</h1>
{% bibliography -f dissertations %}

</div>
