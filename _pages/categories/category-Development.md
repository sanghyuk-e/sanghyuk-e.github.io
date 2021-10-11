---
layout: archive
permalink: /categories/Development
title: "Development 카테고리의 포스트"
author_profile: true
sidebar_main: true
search : false
---

{% assign posts = site.categories.Development | sort:"date" | reverse %}

{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}