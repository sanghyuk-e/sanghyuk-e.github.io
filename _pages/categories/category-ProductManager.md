---
layout: archive
permalink: /categories/ProductManager
title: "Product Manager 카테고리의 포스트"
author_profile: true
sidebar_main: true
search : false
---

{% assign posts = site.categories.ProductManager | sort:"date" | reverse %}

{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}