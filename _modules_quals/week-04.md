---
title: Building Accessible Interfaces
week: Week 4
start: Oct 13
---
{% assign next = page.start |  split: "," %}
{% assign weekday = page.start |  split: "," %}
{% for i in (1 .. 7) %}
   {% assign next = next[0] | date: "%s" | plus: 86400 | date: "%b %d" | split: "," %}
   {% assign weekday = weekday | concat: next %}
{% endfor %}

{{weekday[0]}}
: Building Accessible Interfaces
  : [Slides](slides/best-practices.html)
: **Skill Goal**{: .label .label-yellow} Accessibility Assessment
  : [Slides](slides/capstoneslides)
: **Read**{: .label .label-blue} [An epidemiology-inspired, large-scale analysis of mobile app accessibility](https://dl.acm.org/doi/10.1145/3348797)
: **HW 2 due**{: .label .label-red} [Plain Language](assignmens/plain-language.md)
: **HW 3 assigned**{: .label .label-red}  [Improve accessibility of a thing](assignments/technology-implementation.html) 

{{weekday[2]}}
: TBD (maybe automating analysis?)
  : Student Pair
: **Read**{: .label .label-blue} Accessibility and Grading [Ungrading for access and equity](https://www.insidehighered.com/news/student-success/academic-life/2023/04/11/ungrading-form-access-equality-classroom); Accessibility and Course design: [Creating an accessible cours](https://sds.cornell.edu/resources/faculty-staff/universal-design-instruction); Accessibility Curriculum: [Teach Access on Fundamentals](https://teachaccess.org/wp-content/uploads/2018/03/Teaching-Accessibility-Fundamental-Skills-and-Concepts.pdf)
: **Optional/perhaps of interest** [RIT research project on teaching accessibility](https://cair.rit.edu/teaching-accessibility/{; [Teaching Accessible Computing Book](https://bookish.press/tac)
