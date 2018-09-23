---
layout: default
title: Welcome to DND Items
---
# Testing
{% for item in site.items %}
  <h2>{{ item.name }} - {{ item.type }} , {{ item.rarity }}</h2>
  <p>{{ item.content | markdownify }}</p>
  <p>{{ item.source }}</p>
{% endfor %}
