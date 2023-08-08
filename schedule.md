---
layout: page
title: Schedule
description: The weekly event schedule.
---

# Weekly Schedule
This schedule outlines all topics of the course and has links to all lecture slides, both in chinese and english.

{% for module in site.modules %}
{{ module }}
{% endfor %}