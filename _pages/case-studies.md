---
title: "Case Studies"
layout: archive
permalink: /case-studies/
entries_layout: list
---

{% assign posts = site.categories["Case Studies"] | sort: "sort_order" %}

{% for post in posts %}
  {% include archive-single.html post=post type=page.entries_layout %}
{% endfor %}
