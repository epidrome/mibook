---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: false
---

{% include base_path %}

<div class="grid__wrapper">
  {% for item in site.gallery %}
    {% include gallery-item.html type="grid" %}
  {% endfor %}
</div>
