---
layout: page
permalink: /publications/
title: publications
description: Publications in reversed chronological order.
years: [2021, 2020, 2018, 2016, 2015, 2014]
---

For a complete list, see [Google Scholar](https://scholar.google.com/citations?user=5W10qpIAAAAJ&hl=en).

{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
