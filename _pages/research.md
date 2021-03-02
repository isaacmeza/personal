---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research interests are in the intersection of Probability & Statistics and Multi-arm bandits, as well as Machine Learning methods in Causal Inference.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
