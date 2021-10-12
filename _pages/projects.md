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


<!-- ### 2020/2021 (spring)

- "Mathematical models of social evolution". [Toulouse Summer School in Quantitative Social Sciences](https://www.tse-fr.eu/toulouse-summer-school-quantitative-social-sciences){:target="\_blank"}.

### 2020/2021 (fall)

- "Introduction to Ecology for Economists". [Master 2 Environmental and Natural Resources Economics](https://www.tse-fr.eu/erna){:target="\_blank"}.

- "Population Demography and Evolutionary Ecology" (co-taught with [Simon Blanchet](http://simonblanchet.weebly.com/){:target="\_blank"}. [Master 2 Environmental and Natural Resources Economics](https://www.tse-fr.eu/erna){:target="\_blank"}.

### 2019/2020 (fall)

- "Introduction to Ecology for Economists". [Master 2 Environmental and Natural Resources Economics](https://www.tse-fr.eu/erna){:target="\_blank"}.

- "Population Demography and Evolutionary Ecology" (co-taught with [Simon Blanchet](http://simonblanchet.weebly.com/){:target="\_blank"}. [Master 2 Environmental and Natural Resources Economics](https://www.tse-fr.eu/erna){:target="\_blank"}.


### 2018/2019 (spring)

- "Advanced Behavioral and Experimental Economics II" (co-taught with [Ingela Alger](https://ingelaalger.weebly.com/){:target="\_blank"}, [Michael Becher](https://www.ie.edu/school-global-public-affairs/faculty-and-research/faculty/michael-becher/){:target="\_blank"}, [Paul Seabright](https://paulseabright.com/){:target="\_blank"},
and
[Jonathan Stieglitz](https://www.iast.fr/people/jonathan-stieglitz){:target="\_blank"}).
[Doctoral program](https://www.tse-fr.eu/doctoral-program){:target="\_blank"}.

### 2018/2019 (fall)

- "Introduction to Ecology for Economists".
[Master 2 Environmental and Natural Resources Economics](https://www.tse-fr.eu/erna){:target="\_blank"}.

- "Population Demography and Evolutionary Ecology" (co-taught with [Simon Blanchet](http://simonblanchet.weebly.com/){:target="\_blank"} and
[Jean Clobert](https://scholar.google.com/citations?user=aq9GnD4AAAAJ){:target="\_blank"}). [Master 2 Environmental and Natural Resources Economics](https://www.tse-fr.eu/erna){:target="\_blank"}.


### 2017/2018 (fall)

- "Economics and the Environment for Economists" (co-taught with
[Jean-Pierre Amigues](https://www.tse-fr.eu/people/jean-pierre-amigues){:target="\_blank"},
[Alexis Chaine](https://scholar.google.com/citations?user=U7NInY8AAAAJ){:target="\_blank"},
[Jean Clobert](https://scholar.google.com/citations?user=aq9GnD4AAAAJ){:target="\_blank"},
[Étienne Danchin](http://www.edanchin.fr/?lang=en){:target="\_blank"},
[Marion Desquilbet](https://www.tse-fr.eu/people/marion-desquilbet){:target="\_blank"},
[Michel Loreau](https://scholar.google.co.uk/citations?user=eQNM6tAAAAAJ){:target="\_blank"},
and
[Claire de Mazancourt](https://scholar.google.fi/citations?user=mwd0mqUAAAAJ&hl=fi){:target="\_blank"}. [Master 2 Environmental and Natural Resources Economics](https://www.tse-fr.eu/erna){:target="\_blank"}.

- "Economics and Evolution" (co-taught with [Ingela Alger](https://ingelaalger.weebly.com/){:target="\_blank"}, Jean-Pierre Amigues, [Paul Seabright](https://paulseabright.com/){:target="\_blank"}, and
[Jörgen Weibull](https://sites.google.com/site/joergenweibull/){:target="\_blank"}).
[Doctoral program](https://www.tse-fr.eu/doctoral-program){:target="\_blank"}. -->

<!--For now, this page is assumed to be a static description of your courses. You can convert it to a collection similar to `_projects/` so that you can have a dedicated page for each course.

Organize your courses by years, topics, or universities, however you like!-->
