---
title: Data/AI & Accessibility
week: Week 8
start: Nov 10
---
{% assign next = page.start |  split: "," %}
{% assign weekday = page.start |  split: "," %}
{% for i in (1 .. 7) %}
   {% assign next = next[0] | date: "%s" | plus: 86400 | date: "%b %d" | split: "," %}
   {% assign weekday = weekday | concat: next %}
{% endfor %}


{{weekday[0]}}
: AI & Accessibility : Student Pair (Summary; Discussant)
: **Read**{: .label .label-blue} TBD


{{weekday[2]}}
: Accessible Data Visualization 
  : Student pair
: **Read**{: .label .label-blue} [Beyond Vision Impairments: Redefining the Scope of Accessible Data Representations](https://ieeexplore.ieee.org/abstract/document/10411059?casa_token=S322L-0vUCsAAAAA:7B94PN3INQVxZmHRP8IvahtS2MG4eKMa5q6M84mFLjdMTkCjuXcWKVs5niMRFXDlXyrDQEmhAy_58g); [Increasing Data Equity in Accessibility](https://arxiv.org/abs/2210.01902) 
: **Optional**: [VoxLens: Making Online Data Visualizations Accessible With an Interactive JavaScript Plug-In](https://dl.acm.org/doi/fullHtml/10.1145/3491102.3517431)

