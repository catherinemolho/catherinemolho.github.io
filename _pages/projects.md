<!-- ---
layout: page
permalink: /projects/
title: projects
description: ongoing projects
nav: true
---

{% assign sorted_projects = site.projects | sort: "importance" %}
<!-- Generate cards for each project -->
{% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.html %}
    {% endfor %}
    </div>
  </div>
{% else %}
  <div class="grid">
    {% for project in sorted_projects %}
      {% include projects.html %}
    {% endfor %}
  </div>
{% endif %} -->
