---
layout: archive
permalink: /categories/ProductManager
title: "Post about Product Manager"
author_profile: true
sidebar_main: true
search : false
---

{% assign posts = site.categories.ProductManager | sort:"date" | reverse %}

{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}