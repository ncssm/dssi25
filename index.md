---
layout: home
title: Home
nav_order: 1
nav_exclude: false
permalink: index.html
---

# NCSSM's 2024 Data Science Summer Institute

{: .mb-2 }
NCSSM-Morganton, July 8-12, 2024
{: .mb-2 .fs-6 .text-grey-dk-000 }

[Jupyter Link](https://datahub.ncssm.edu){: .btn .btn-orange} [Sync Materials](#){: .btn .btn-purple}

## Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

## Schedule
{% for module in site.modules %}
{{ module }}
{% endfor %}
