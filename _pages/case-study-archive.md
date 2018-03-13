---
layout: archive
title: "Case Study"
permalink: /case-study/
author_profile: false
---

{% include base_path %}

<div class="grid__wrapper">
  {% for item in site.case-study %}
    {% include gallery-item.html type="grid" %}
  {% endfor %}
</div>
