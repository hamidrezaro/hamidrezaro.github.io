---
title: "A Comprehensive Analysis of the Effects of Network Quality of Service on Robotic Telesurgery"
collection: publications
permalink: /publication/network-qos-effects-robotic-telesurgery
excerpt: "This work introduces NetFI and quantifies how packet loss, delay, and communication loss affect telesurgical performance, safety, and workload at both the task and motion-primitive levels."
date: 2026-03-06
venue: "ICRA 2026"
publication_label: "Submitted to"
paperurl: /files/icra2026.pdf
header:
  teaser: /files/icra2026.png
---
<img src="{{ '/files/icra2026.png' | relative_url }}" alt="NetFI telesurgery quality-of-service emulation architecture" style="max-width: 100%; height: auto;" />

This paper studies how realistic network degradations shape the safety and usability of robotic telesurgery. It introduces NetFI, a model-based fault injection tool that emulates packet loss, delay, and communication loss using stochastic quality-of-service models derived from real network behavior, then integrates the emulator into a telesurgical simulation platform for controlled experimentation.

Through a user study with participants of different proficiency levels, the work analyzes both overall task outcomes and fine-grained motion primitives using objective performance metrics, safety events, and subjective workload measures. The results identify which surgical actions are most vulnerable to degraded network conditions and provide practical evidence for designing network-aware control, autonomy, and mitigation strategies.

[Download paper here]({{ page.paperurl | relative_url }})
