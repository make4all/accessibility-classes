---
title: Fabrication 
week: Week 4
start: Oct 20
---
{% assign next = page.start |  split: "," %}
{% assign weekday = page.start |  split: "," %}
{% for i in (1 .. 7) %}
   {% assign next = next[0] | date: "%s" | plus: 86400 | date: "%b %d" | split: "," %}
   {% assign weekday = weekday | concat: next %}
{% endfor %}


{{weekday[0]}}
: Fabrication & Accessibility
  : [Slides](slides/3dprinting.html)


{{weekday[2]}}
: (in CSE 2 G15) Working on Lasercutting Project
  - Fabrication lab: Making an accessible thing using a laser cutter
