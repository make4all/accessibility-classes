---
layout: page
title: Syllabus
description: >-
    Course policies and information.
---

# Syllabus
{:.no_toc}
---

{% for topic in site.syllabus %}
<details>
<summary> {{topic.title}}</summary>
{{ topic }}
</details>
{% endfor %}

