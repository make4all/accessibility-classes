---
title: AT Around us and Design Models
week: Week 3
start: Oct 6
---
{% assign next = page.start |  split: "," %}
{% assign weekday = page.start |  split: "," %}
{% for i in (1 .. 7) %}
   {% assign next = next[0] | date: "%s" | plus: 86400 | date: "%b %d" | split: "," %}
   {% assign weekday = weekday | concat: next %}
{% endfor %}

{{weekday[0]}}
: Practice with Plain Language 
  : [Slides](slides/plain-language.html) 
: **Read**{: .label .label-blue} [Plain language writing](https://www.forbes.com/sites/andrewpulrang/2020/10/22/plain-language-writing---an-essential-part-of-accessibility/) and [Plain language](https://pudding.cool/2022/02/plain/)
: **HW 1 slides due**{: .label .label-red} [At Around US](assignments/finding-accessibility.html)
: **HW 2 assigned**{: .label .label-red} [Plain Language](assignmens/plain-language.md)
(drop  [Research Paper Analysis](assignments/disabilityjustice.html) ?)


{{weekday[2]}}
: AT Around Us Presentations
  : 60 minutes of AT Around Us presentations

