---
title: Example of Reveal Slides
description: A slide deck written in Reveal
layout: reveal
load_dir: "1_example_reveal"
author: Test
date: 2025-08-02 
comments: true
---

{% if page.load_dir %}
   {% assign slide_dir = page.load_dir %}
{% else %}
   {% assign slide_dir = page.name %}
{% endif %}

{% for slide_page in site.pages %}
{% assign slide_page_path = slide_page.url | split:'/' %}
{% if slide_page_path[1] == "slides" and slide_page_path[2] == slide_dir  %}
{% if slide_page_path.size == 4 %}
<section id={{slide_page_path[3]}} data-markdown>
<textarea data-template>
{{slide_page.content}}
</textarea>
</section>

{% endif %}
{% endif %}
{% endfor %}
