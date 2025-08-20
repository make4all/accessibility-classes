---
title: XR/VR/AR
week: Week 10
start: Nov 24
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
: **Read**{: .label .label-blue} [A systematic literature review of handheld augmented reality solutions for people with disabilities](https://www.mdpi.com/1424-8220/22/20/7719); 
: **Try**{: .label .label-yellow} Available now: [OverTHERE](https://apps.apple.com/us/app/overthere/id1126056833); [Honor Everywhere](https://www.oculus.com/experiences/go/1634724596608007/); [Accessibility, Disabilities, and Virtual Reality Solutions](https://educatorsinvr.com/2019/05/31/accessibility-disabilities-and-virtual-reality-solutions/)
: **Optional** [SeeingVR: A set of tools to make virtual reality more accessible to people with low vision](https://dl.acm.org/doi/fullHtml/10.1145/3290605.3300341); [AR4VI: AR as an accessibility tool for people with visual impairments](https://ieeexplore.ieee.org/abstract/document/8088507?casa_token=1ljGqVmunOsAAAAA:AmtEC4AL2x5t0A8p51rBPTpBrw8Utxub6qUX5OE1L6AHg08iDlgGXkLuXOWl0Oo4XktQRNICFNBXbg).

{{weekday[2]}}
: Project Checkpoint Discussion : (**HW 5**{: .label .label-red}  [Proposal](assignments/checkpoint.html))
: **HW 7 assigned**{: .label .label-red}  [Final Project](assignments/final.html) 

