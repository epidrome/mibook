---
layout: archive
title: "Quotes"
permalink: /quotes/
author_profile: false
---

<div class="grid__wrapper">
  {% for item in site.quotes %}
    {% include gallery-item.html type="grid" %}
  {% endfor %}
</div>
