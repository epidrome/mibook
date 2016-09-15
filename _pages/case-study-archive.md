---
layout: archive
title: "Case Study"
permalink: /case-study/
author_profile: false
---

{% include base_path %}

<div class="grid__wrapper">
  {% for post in site.case-study %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
