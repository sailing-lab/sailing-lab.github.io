---
layout: page
permalink: /publications/
title: publications
description: <a href="http://www.cs.cmu.edu/~epxing/publications-2021.html">Link to Publications</a>
years: []
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
