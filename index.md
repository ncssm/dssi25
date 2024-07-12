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

[Jupyter Link](https://datahub.ncssm.edu){: .btn .btn-orange} [Sync Materials](https://datahub.ncssm.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fncssm%2Fdssi24-materials&urlpath=lab%2Ftree%2Fdssi24-materials%2F&branch=main){: .btn .btn-purple}

![](https://github.com/ncssm/dssi24/blob/e81e45b747cfa94e8e2c95aa546910699ed46111/assets/images/PXL_20240709_155726902.jpg)

## Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

## Schedule
{% for module in site.modules %}
{{ module }}
{% endfor %}
