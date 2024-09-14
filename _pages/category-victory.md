---
title: "승리의 기록"
layout: archive
permalink: /victory
---

{% assign posts = site.categories.victory %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
