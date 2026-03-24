---
title: "Women, Europe, and Antifascism in the Early 20th Century"
layout: base
date: 2025-10-21
header-image: "/assets/images/sw-table.jpg"
header-title: Women, Europe, and Antifascism in the Early 20th Century
header-subtitle: Biographies
header-position: 35% center
---

# Women, Europe, and Antifascism in the Early 20th Century

This is your class project site, built with the [Xanthan framework](https://xanthan-web.github.io/xanthan/). Everything you see here is a placeholder — the title above, the essay topics, the images. 

To get a sense of what a finished project can look like, this template includes three sample essays on Southwest food history, generated with AI as stand-ins for real student work. Browse them to see how essays can use images, pull quotes, and scroll-driven backgrounds. Then start replacing them with your own material.

The card grid below links to the sample essays. The info on these cards come from the essay pages themselves. As students publish their essaysm, these will showcase students' work as the project develops.

{% assign all_pages = site.pages %}
{% assign cards = all_pages | where_exp: "p", "p.path contains 'essays/'" | where_exp: "p", "p.path != 'essays/index.md'" %}

{% include nav/card-grid.html cards=cards %}

