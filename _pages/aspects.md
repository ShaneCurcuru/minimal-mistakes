---
layout: archive
title: "aspects"
permalink: /aspects
author_profile: false
---

{% include base_path %}

<h2>{{ site.aspects.excerpt }}</h2>

{% for post in site.aspects %}
  {% include archive-single.html %}
{% endfor %}