---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My researches, works tackle problems of designing and controlling robots:

- Design robot. 
- Control robot.
- AI in robotics.

All works are tested in simulations and in real robots.
<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
