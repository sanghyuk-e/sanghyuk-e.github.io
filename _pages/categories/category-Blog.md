---
layout: archive
permalink: /categories/Blog
title: "Post about Blog"
author_profile: true
sidebar_main: true
search : false
---

{% assign posts = site.categories.Blog | sort:"date" | reverse %}

{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}