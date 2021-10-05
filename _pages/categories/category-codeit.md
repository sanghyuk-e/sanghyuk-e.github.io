---
layout: archive
permalink: /categories/CodeIt
title: "Post about Code it"
author_profile: true
sidebar_main: true
search : false
---

{% assign posts = site.categories.codeit | sort:"date" | reverse %}

{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}