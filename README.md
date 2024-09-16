---
layout: home
title: BioEngineering 10
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: Just the Class
---

# BioEngineering 10
[bCourses](https://bcourses.berkeley.edu/courses/1526813){: .btn .btn-blue .mr-2 }
[Ed](https://edstem.org/us/courses/41881/discussion/){: .btn .btn-purple }

## Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

## Schedule

{% for module in site.modules %}
{{ module }}
{% endfor %}