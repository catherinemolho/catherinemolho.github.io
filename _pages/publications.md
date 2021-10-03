---
layout: page
permalink: /research/
title: research
description: journal articles, preprints, and papers in conference proceedings
years: [2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2012, 2011, 2009, 2008, 2007, 2006]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f publications -q @*[year={{y}}]* %}
{% endfor %}

</div>
