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
  <li><span class="label label-blue">Discussion</span>: Traditional instructional sessions focusing on assigned course materials.</li>
  <li><span class="label label-red">Lab</span>: Hands-on sessions applying concepts in a practical setting.</li>
  <li><span class="label label-green">Present</span>: Sessions where students present their projects or research.</li>
<li><span class="label label-yellow">Field Trip</span>: Educational visit to relevant locations.</li>

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
