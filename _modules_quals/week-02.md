---
title: Accessible Presentations and AT Around Us presentations
week: Week 2
start: Sep 29
---
{% assign next = page.start |  split: "," %}
{% assign weekday = page.start |  split: "," %}
{% for i in (1 .. 7) %}
   {% assign next = next[0] | date: "%s" | plus: 86400 | date: "%b %d" | split: "," %}
   {% assign weekday = weekday | concat: next %}
{% endfor %}

**Goals**
: How to create accessible documents
: How to present accessibly 
: Introduction to how to use plain language 
: Discussion of best practices in returning research to the disability community, such as member checking, workshops, and creation of prestige opportunities for community members 

{{weekday[0]}}
: Presenting Accessibly
  : [Slides](slides/presenting-accessibly.html)
: **Skill Goal**{: .label .label-yellow} Describe a person  (see [slides](slides/presenting-accessibly) for in class exercise)
  : Bring a visual representation of yourself to class
: Read about [Creating Accessible Figures and Tables (DIS)](https://dis.acm.org/2023/creating-accessible-figures-and-tables/) and try out the [Image ALT Text Tutorial](https://webaim.org/techniques/alttext/)
: Read ["It's Complicated" (Bennett et al)](https://dl.acm.org/doi/10.1145/3411764.3445498) 
: *Optional*: Read [Dungeons and Dragons taught me how to write ALT text](https://ericwbailey.website/published/dungeons-and-dragons-taught-me-how-to-write-alt-text/)
:  <i class="fa-solid fa-house-laptop" aria-hidden="true"/>  Optional: ["Living Disability Theory: Reflections on Access, Research, and Design." (Hofmann, et al)](https://make4all.org/wp-content/uploads/3373625.3416996.pdf)
: **HW 1 due**{: .label .label-red} <i class="fa-solid fa-house-laptop" aria-hidden="true"/>  [At Around US](assignments/finding-accessibility.html)

{{weekday[2]}}
: AT Around Us Presentations
: Plain Language
  : [Slides](slides/plain-language.html) - 60 minutes of AT Around Us presentations
: [Plain language writing](https://www.forbes.com/sites/andrewpulrang/2020/10/22/plain-language-writing---an-essential-part-of-accessibility/)
: [Plain language](https://pudding.cool/2022/02/plain/)
: [Disability Dongles](https://blog.castac.org/2022/04/disability-dongle/) by Liz Jackson, Alex Haagaard, Rua Williams
: **Reading** {: .label .label-purple} Post your response to [reading questions for these readings on Ed](https://edstem.org/us/courses/56844/discussion/4659767) 
: <i class="fa-solid fa-house-laptop" aria-hidden="true"/>  Optional: [Design, Disability and Knowing the 'Other'](https://dl.acm.org/doi/fullHtml/10.1145/3290605.3300528) 
