---
title: ASSETS & Proposals
week: Week 7
start: Nov 3
---
{% assign next = page.start |  split: "," %}
{% assign weekday = page.start |  split: "," %}
{% for i in (1 .. 7) %}
   {% assign next = next[0] | date: "%s" | plus: 86400 | date: "%b %d" | split: "," %}
   {% assign weekday = weekday | concat: next %}
{% endfor %}


{{weekday[0]}}
: Project Proposals Discussion : (**HW 4**{: .label .label-red}  [Proposal](assignments/proposal.html))
: **HW 5 assigned**{: .label .label-red} [Checkpoint](assignments/checkpoint.html) 


{{weekday[2]}}
: Best of ASSETS 
