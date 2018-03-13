---
layout: splash
author_profile: false
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/header.jpg
  cta_label: "Buy the greek e-book"
  cta_url: "https://leanpub.com/pibook"
  caption: "Photo credit: [**SRI International**](https://www.sri.com)"
caption: 'Building collaborative systems for an ecosystem of users, devices, and services.'
intro:
    - excerpt: 'The book `Making Interactivity` describes the next stage in the evolution of `Interaction Design`. Instead of low- and hi-fidelity prototypes, it encourages the lean development of interactive minimum viable products (MVP).'
---

<div class="feature__wrapper">

  {% assign random = site.time | date: "%s%N" | modulo: site.quotes.size %}

  {% include feature_col.html id="quotes" type="left" index=random %}

  {% assign random = site.time | date: "%s%N" | modulo: site.gallery.size %}

  {% include feature_col.html id="gallery" type="center" index=random %}

  {% assign random = site.time | date: "%s%N" | modulo: site.case-study.size %}

  {% include feature_col.html id="case-study" type="right" index=random %}

<div>
