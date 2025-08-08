---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

# Calendar

{% assign today_date = 'now' | date: '%s' | plus: 0 %}
{% for module in site.modules %}
   {% assign module_start_date = module.start | date: '%s' | plus: 0  %}
   {% assign module_end_date = module_start_date | plus: 604800 %} 
   {% if today_date >= module_start_date and today_date <= module_end_date %}
<details open>
   {% else %}
<details>
   {% endif %}
<summary> {{module.start}} ({{module.week}}): {{module.title}}</summary>
{{ module }}
</details>
{% endfor %}
