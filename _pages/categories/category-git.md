---
layout: archive
permalink: /categories/git
title: "Post about git"
author_profile: true
sidebar_main: true
search : false
---

{% assign posts = site.categories.git | sort:"date" | reverse %}

{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}