---
title: Biographies
layout: base
header-title: Biographies
---

# Biographies of Anti-Fascist Women in Europe in the Early 20th Century

{% assign all_pages = site.pages %}
{% assign cards = all_pages | where_exp: "p", "p.path contains 'essays/'" | where_exp: "p", "p.path != 'essays/index.md'" %}

{% include nav/card-grid.html cards=cards %}
