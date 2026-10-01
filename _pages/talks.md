---
layout: page
title: talks
permalink: /talks/
description: Documents related to talks I've given.
nav: true
nav_order: 4
horizontal: false
---

{% assign talks = site.talks | sort: 'date' | reverse %}

{% for item in talks %}
  <h3>{{ item.title }}</h3>
  <p>{{ item.content }}</p>
{% endfor %}
