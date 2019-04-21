---
layout: archive
title: "Coding"
permalink: /coding/
author_profile: true
---

{% include base_path %}

{% if author.github %}
  You can also find more of work on <u><a href="{{author.github}}">my GitHub account</a>.</u>
{% endif %}

{% for post in site.coding reversed %}
  {% include archive-single-coding.html %}
{% endfor %}
