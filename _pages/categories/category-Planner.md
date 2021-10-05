---
layout: archive
permalink: /categories/Planner
title: "Post about Planner"
author_profile: true
sidebar_main: true
search : false
---

{% assign posts = site.categories.Planner | sort:"date" | reverse %}

{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}