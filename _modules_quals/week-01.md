---
title: Introduction to Disability & Accessibility & Accessible Documents
week: Week 1
start: Sep 22
---

{% assign next = page.start |  split: "," %}
{% assign weekday = page.start |  split: "," %}
{% for i in (1 .. 6) %}
   {% assign next = next[0] | date: "%s" | plus: 86400 | date: "%b %d" | split: "," %}
   {% assign weekday = weekday | concat: next %}
{% endfor %}

{{weekday[0]}}
**No Class**{: .label .label-black}

{{weekday[2]}}
: Introduction to Course
  : [Slides](slides/introduction.html)
: **Skill Goal**{: .label .label-yellow} Learn how accommodations can make a meeting more inclusive (see slides for In class Exercise and post on our [Discussion Board]({{site.discussion}}))
: **HW 1 out**{: .label .label-red } <i class="fa-solid fa-house-laptop" aria-hidden="true"/>  [At Around US](assignments/finding-accessibility.html)
  
