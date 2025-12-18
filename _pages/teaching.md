---
title: Teaching
permalink: /teaching/
layout: single
author_profile: true
---

{% assign courses = site.teaching | sort: "title" %}
{% for course in courses %}
### {{ course.title }}
{{ course.content }}
{% endfor %}
