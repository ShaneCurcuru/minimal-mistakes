---
layout: archive
title: "ways"
permalink: /ways
author_profile: false
---

{% include base_path %}

### {{ site.ways.excerpt }}

{% for post in site.ways %}
  {% include archive-single.html %}
{% endfor %}