---
layout: page
title: Schedule
description: Listing of course modules and topics
nav_order: 3
---

# Schedule

{: .note}
>
> This schedule is your go-to resource for the most up-to-date syllabus, reading materials, and assignments. While we will strive to stick to this schedule, please understand that it is not set in stone -- updates may occur. Should there be any important changes to the schedule, assignments, or reading materials, you'll receive an email notification!
>
> Here's a quick overview to the different types of class meetings we'll have:
> 
> <ul>
>  <li><span class="label label-blue">Discussion</span>: Sessions that combine lecturing with discussions, emphasizing critical engagement with the assigned materials.</li>
>  <li><span class="label label-red">Lab</span>: Hands-on sessions applying concepts in a practical setting.</li>
>  <li><span class="label label-green">Present</span>: Sessions where students present their projects or research.</li>
><li><span class="label label-yellow">Field Trip</span>: Visit to Princeton University Library Special Collections.</li>
> </ul>


{% for module in site.modules %}
  {{ module }}
  {% if module.title == "Week 6 - Distant Reading" %}
> 🍂 **Fall Recess** 🍂  
>
> Enjoy a well-deserved break!
{: .notice--fall-recess }
  {% endif %}
{% endfor %}

{% for module in site.modules %}
  {{ module }}
  {% if module.title == "Week 11 - Python for the Curious" %}
> 🦃 **Thanksgiving Recess** 🌽 
>
> Enjoy a well-deserved break!
{: .notice--fall-recess }
  {% endif %}
{% endfor %}
