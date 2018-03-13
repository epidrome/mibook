---
layout: archive
title: "Quotes"
permalink: /quotes/
author_profile: false
---

{% include base_path %}

<div class="grid__wrapper">
  {% for item in site.quotes %}
    {% include gallery-item.html type="grid" %}
  {% endfor %}
</div>
