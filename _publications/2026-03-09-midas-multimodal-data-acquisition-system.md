---
title: "MiDAS: A Multimodal Data Acquisition System and Dataset for Robot-Assisted Minimally Invasive Surgery"
collection: publications
permalink: /publication/midas-multimodal-data-acquisition-system
excerpt: "MiDAS is an open, platform-agnostic system for synchronized multimodal data collection in robotic surgery, enabling non-invasive sensing and releasing new datasets for activity recognition research."
date: 2026-03-09
venue: "The International Journal of Medical Robotics and Computer Assisted Surgery"
publication_label: "Submitted to"
paperurl: /files/ijmrcas2026.pdf
header:
  teaser: /files/ijmrcas2026.png
---
<img src="{{ '/files/ijmrcas2026.png' | relative_url }}" alt="MiDAS multimodal data acquisition system overview" style="max-width: 100%; height: auto;" />

This paper introduces MiDAS, an open-source and platform-agnostic multimodal data acquisition system for robot-assisted minimally invasive surgery. The system synchronizes external hand tracking, RGB-D sensing, pedal signals, and surgical video without requiring proprietary robot interfaces, making it easier to collect rich datasets across both research and clinical robotic platforms.

The paper validates these non-invasive sensing modalities against internal robot telemetry and shows that external motion signals can support downstream gesture recognition with performance comparable to robot kinematics in some settings. It also releases new multimodal datasets, including realistic suturing data from da Vinci Xi training scenarios, to support reproducible research in surgical activity understanding.

[Download paper here]({{ page.paperurl | relative_url }})
