---
title: "Women, Europe, and Antifascism in the Early 20th Century"
layout: base
date: 2025-10-21
header-image: "/assets/images/antifascist-march-mural-hh-2.jpeg"
header-title: Women, Europe, and Antifascism in the Early 20th Century
header-subtitle: Biographies
header-position: 35% center
---

# Women, Europe, and Antifascism in the Early 20th Century

This website explores the biographies and histories of prominent European and American women antifascist activists from the early 20th century. 

This project will introduce readers to historical antifascism (1914-1945) by emphasizing the role of European and American women’s actions, writings, organizing, and participation within the transnational antifascism movement of the interwar period.

## How to Navigate this Page:

The card grid below links to descriptive essays about each historical figure - click to explore and learn! 

{% assign all_pages = site.pages %}
{% assign cards = all_pages | where_exp: "p", "p.path contains 'essays/'" | where_exp: "p", "p.path != 'essays/index.md'" %}

{% include nav/card-grid.html cards=cards %}

