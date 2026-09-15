---
title: "Sitemap"
permalink: /sitemap/
layout: single
author_profile: true
---

- [About](/)
- [Projects](/projects/)
- [Research](/research/)
- [CV](/cv/)

## Project pages
{% assign projects = site.portfolio | sort: 'order' %}
{% for project in projects %}
- [{{ project.title }}]({{ project.url }})
{% endfor %}

