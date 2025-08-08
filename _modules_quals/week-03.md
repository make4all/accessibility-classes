---
title: Introduction to Disability & Accessibility & Accessible Documents
week: Week 3
start: Oct 6
---

{% assign next = page.start |  split: "," %}
{% assign weekday = page.start |  split: "," %}
{% for i in (1 .. 6) %}
   {% assign next = next[0] | date: "%s" | plus: 86400 | date: "%b %d" | split: "," %}
   {% assign weekday = weekday | concat: next %}
{% endfor %}

{{weekday[0]}}
