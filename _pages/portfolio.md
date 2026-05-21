---
layout: archive
title: "Projects"
permalink: /portfolio/
author_profile: true
---

Thesis work, laboratory projects, and demos from graduate and undergraduate study.

## Master's programme — Innopolis University

Research arc: cable-driven teleoperation → bilateral KUKA control → VR interface → peg-in-hole with haptics → four-mode thesis benchmark.

{% include base_path %}

{% assign master_projects = site.portfolio | where_exp: "item", "item.categories contains 'master'" | sort: 'date' | reverse %}
<div class="portfolio-grid">
{% for post in master_projects %}
  {% include archive-portfolio-card.html %}
{% endfor %}
</div>

## Bachelor's programme — Nile University

{% assign bachelor_projects = site.portfolio | where_exp: "item", "item.categories contains 'bachelor'" | sort: 'date' | reverse %}
<div class="portfolio-grid">
{% for post in bachelor_projects %}
  {% include archive-portfolio-card.html %}
{% endfor %}
</div>
