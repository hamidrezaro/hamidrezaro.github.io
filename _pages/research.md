---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Towards a Safety Engine for Robotic Assisted Tele-Surgery

My current research project involves developing a safety engine for robotic tele-surgery that focuses on ensuring the reliability of robotic laparoscopic tele-surgery systems and prioritizing patient safety. Our main objectives are to analyze these systems, construct safety models and engines, and establish an end-to-end hazard detection and recovery architecture. This architecture includes activity recognition, error/fault detection, and recovery strategies to address potential risks. By detecting potentially unsafe control commands issued in the cyber layer, we can estimate the likelihood, timing, and risk of safety hazards. Additionally, we aim to mitigate adverse consequences in the physical layer by implementing safe and corrective response actions. To achieve this, we employ data-driven recognition and prediction machine learning models along with knowledge-based surgical operation hierarchical process models. By utilizing these tools, we can develop recovery plans that the robot can execute until the source of errors or security attacks is eliminated.

<p style="text-align:center;"><img src="/images/system_diag.png" width="700" height="588"></p>


{% include base_path %}

{% for post in site.researh reversed %}
  {% include archive-single.html %}
{% endfor %}
