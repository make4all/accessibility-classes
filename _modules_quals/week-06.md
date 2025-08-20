---
title: Inclusive Study Design
week: Week 6
start: Nov 10
---
{% assign next = page.start |  split: "," %}
{% assign weekday = page.start |  split: "," %}
{% for i in (1 .. 7) %}
   {% assign next = next[0] | date: "%s" | plus: 86400 | date: "%b %d" | split: "," %}
   {% assign weekday = weekday | concat: next %}
{% endfor %}


{{weekday[0]}}
: Best practices for inclusive studies  
  : Student Pair
: **Read**{: .label .label-blue} [Anticipate and Adjust](https://dl.acm.org/doi/fullHtml/10.1145/3491102.3501882) CHI 2022
: **HW 3 due**{: .label .label-red}  [Improve accessibility of a thing](assignments/technology-implementation.html) 
: **HW 4 assigned**{: .label .label-red}  [Proposal](assignments/proposal.html) 


{{weekday[2]}}
: No class (ASSETS)
