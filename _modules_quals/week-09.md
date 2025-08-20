---
title: Intersectionality
week: Week 9
start: Nov 17
---
{% assign next = page.start |  split: "," %}
{% assign weekday = page.start |  split: "," %}
{% for i in (1 .. 7) %}
   {% assign next = next[0] | date: "%s" | plus: 86400 | date: "%b %d" | split: "," %}
   {% assign weekday = weekday | concat: next %}
{% endfor %}


{{weekday[0]}}
: Project Checkpoint Discussion : (**HW 5**{: .label .label-red}  [Checkpoint](assignments/checkpoint.html))
: **HW 6 assigned**{: .label .label-red}  [Checkpoint 2](assignments/checkpoint2.html) 

{{weekday[2]}}
: Intersectionality
  : Student pair
: **Read**{: .label .label-blue} Harrington: [Working at the Intersection of Race, Disability and Accessibility](https://dl.acm.org/doi/fullHtml/10.1145/3597638.3608389)
: **Listen/watch**{: .label .label-blue} to one of: [Stop Doing That!](https://www.youtube.com/watch?v=hMr831Ro2-k&feature=youtu.be); [Chicas talk disability](https://www.manhattantimesnews.com/they-thought-i-was-a-criminalpensaron-que-yo-era-una-delincuente/); From time 42:25 [Podcast Website](https://talkingwithtech.podbean.com/e/kevin-williams-lateef-mcleod-black-aac-user-perspectives-on-racism-and-disability/) | [YouTube at Timestamp](https://youtu.be/iTSAK4yRf5A) | [Transcription](https://courses.cs.washington.edu/courses/cse590w/20au/uwnetid/TranscriptBlackAACUserPerspectivesonRacismandDisability_Trim.docx)
