---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---



{% include base_path %}

{% for post in site.researh reversed %}
  {% include archive-single.html %}
{% endfor %}