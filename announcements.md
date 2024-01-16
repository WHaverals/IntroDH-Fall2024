---
layout: page
title: Announcements
nav_exclude: false
description: A feed containing all of the class announcements.
nav_order: 2
---

# Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
