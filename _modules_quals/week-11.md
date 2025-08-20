---
title: XR/VR/AR
week: Week 11
start: Dec 1
---
{% assign next = page.start |  split: "," %}
{% assign weekday = page.start |  split: "," %}
{% for i in (1 .. 7) %}
   {% assign next = next[0] | date: "%s" | plus: 86400 | date: "%b %d" | split: "," %}
   {% assign weekday = weekday | concat: next %}
{% endfor %}


{{weekday[0]}}
: Sustainability
  : Student pair
: **Read**{: .label .label-blue} Kelley-Costello: [A just transition for disabled people](https://www.disabilitydebrief.org/debrief/messy-climate-transitions/); Hamidi and Karachiwalla: ["I'm ok because I'm alive": understanding socio-cultural accessibility barriers for refugees with disabilities in the US](https://dl.acm.org/doi/10.1145/3493612.3520446)
: **Optional**: Anything from the [24w CREATE seminar](https://courses.cs.washington.edu/courses/cse590w/24wi/); [Earth at risk: An urgent call to end the age of destruction and forge a just and sustainable future](https://academic.oup.com/pnasnexus/article/3/4/pgae106/7638480?login=false)


{{weekday[2]}}
: Final Project Presentations

