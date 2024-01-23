---
layout: page
title: Schedule
description: Listing of course modules and topics
nav_order: 3
---

# Schedule

<details>

<summary>Class Meeting Types</summary>

<ul>
  <li><span class="label label-blue">Discussion</span>: Traditional instructional sessions focusing on course material.</li>
  <li><span class="label label-red">Lab</span>: Hands-on sessions applying course concepts in a practical setting.</li>
  <li><span class="label label-green">Trip</span>: Educational visits to relevant locations.</li>
  <li><span class="label label-yellow">Present</span>: Sessions where students present their projects or research.</li>
</ul>
</details>


{% for module in site.modules %}
  {{ module }}
  {% if module.title == "Week 6 - Distant Reading" %}
> 🌴 **Spring Break** 🌴  
>
> Enjoy a well-deserved break!
{: .notice--spring-break }
  {% endif %}
{% endfor %}
