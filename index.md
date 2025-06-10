---
layout: home
title: Home
nav_order: 1
nav_exclude: false
permalink: index.html
---

# NCSSM's 2024 Data Science Summer Institute

{: .mb-2 }
NCSSM-Morganton, June 23-26, 2025
{: .mb-2 .fs-6 .text-grey-dk-000 }

## Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

## Schedule
{% for module in site.modules %}
{{ module }}
{% endfor %}
