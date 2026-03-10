---
layout: archive
title: "Curriculum Vitae"

permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<br />
{% assign cv_url = '/files/cv.pdf' | relative_url %}
{% assign cv_version = site.time | date: '%s' %}
{% assign cv_url_versioned = cv_url | append: '?v=' | append: cv_version %}

<iframe src="{{ cv_url_versioned }}" width="100%" height="500" frameborder="no" border="0" marginwidth="0" marginheight="0"></iframe>

You can download a PDF copy of my CV [here]({{ cv_url_versioned }}).