---
layout: archive
title: "Quotes"
permalink: /quotes/
author_profile: false
---

{% include base_path %}

<div class="grid__wrapper">
  {% for post in site.quotes %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
