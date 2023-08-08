---
layout: home
title: Home
nav_exclude: true
seo:
  type: Course
  name: Discrete Mathematics, SHNU
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

<!-- {% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %} -->

## About the Class

To be continued.

See the [Syllabus page](syllabus.md) for more details on course policies.

## Course Information

To be continued.


# Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}