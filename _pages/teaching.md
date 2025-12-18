---
title: Teaching
permalink: /teaching/
layout: single
author_profile: true
---

{% for course in site.teaching %}
### {{ course.title }}
{{ course.content }}
{% endfor %}
