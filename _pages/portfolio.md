---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

Some collections of places I visited

<nbsp>

{% include base_path %}


{% assign ordered_pages = site.gallery | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}


<!-- {% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %} -->

