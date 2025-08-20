---
title: Accessible Presentations and Plain Language
week: Week 2
start: Sep 29
---
{% assign next = page.start |  split: "," %}
{% assign weekday = page.start |  split: "," %}
{% for i in (1 .. 7) %}
   {% assign next = next[0] | date: "%s" | plus: 86400 | date: "%b %d" | split: "," %}
   {% assign weekday = weekday | concat: next %}
{% endfor %}

{{weekday[0]}}
: Accessible design models 
  : (Student Pair: )
: **Read**{: .label .label-blue}  [Accessibility in Software Practice: A Practitioner’s Perspective](https://dl.acm.org/doi/abs/10.1145/3503508); [Disability Dongles](https://blog.castac.org/2022/04/disability-dongle/) by Liz Jackson, Alex Haagaard, Rua Williams
: Optional: [Design, Disability and Knowing the 'Other'](https://dl.acm.org/doi/fullHtml/10.1145/3290605.3300528); ["Living Disability Theory: Reflections on Access, Research, and Design." (Hofmann, et al)](https://make4all.org/wp-content/uploads/3373625.3416996.pdf)
: **HW 1 assigned**{: .label .label-red} [At Around US](assignments/finding-accessibility.html)

{{weekday[2]}}
: Presenting Accessibly
  : [Slides](slides/presenting-accessibly.html)
: **Skill**{: .label .label-yellow} Describe a diagram or image
: **Read**{: .label .label-blue}  [Creating Accessible Figures and Tables (DIS)](https://dis.acm.org/2023/creating-accessible-figures-and-tables/) 
: **Read**{: .label .label-blue} the most relevant paper ([Decorative and branding](https://dl.acm.org/doi/fullHtml/10.1145/3308558.3313605); [Diagrams](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9028522&casa_token=zZw_rYBgu1AAAAAA:eozpbJ-vvMZjQNt8p6WU91X4uFumPs-yVuMn4PTPRjyMhtsVrprdIEe1JfYOCUdv8SFP_TGd9s965Q&tag=1); [Visualizations](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9555469); [Memes](https://dl.acm.org/doi/10.1145/3308561.3353792); [GUIS](https://dl.acm.org/doi/fullHtml/10.1145/3411764.3445040); ([AR/VR](https://educatorsinvr.com/2019/05/31/accessibility-disabilities-and-virtual-reality-solutions/)); [Rich Interaction Components](https://dl.acm.org/doi/pdf/10.1145/2851613.2851680?casa_token=dOz4huS0TUkAAAAA:zv0PjZk3-T8Bb4X2SfNpdZFuqO2u9v1jpWn5fq0hKZ0se6t5g0oMKLfrAmhlyufcw_3AuJ-ABZ2yWQ);[CAPTCHAs](https://dl.acm.org/doi/10.1145/1518701.1518983)
  : Bring a hard to describe scientific diagram to class
: *Optional*: [Dungeons and Dragons taught me how to write ALT text](https://ericwbailey.website/published/dungeons-and-dragons-taught-me-how-to-write-alt-text/); ["It's Complicated" (Bennett et al)](https://dl.acm.org/doi/10.1145/3411764.3445498)


