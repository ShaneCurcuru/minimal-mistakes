---
layout: archive
title: "aspects"
permalink: /aspects
author_profile: false
---

{% include base_path %}

{% assign thiscol = site.collections | where: "label", "aspects" | first %}
<h2>{{ site.aspects.excerpt }}</h2>

{% for post in site.aspects %}
  {% include archive-single.html %}
{% endfor %}