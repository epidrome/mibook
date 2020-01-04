---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: false
---

<div class="grid__wrapper">
  {% for item in site.gallery %}
    {% include gallery-item.html type="grid" %}
  {% endfor %}
</div>
