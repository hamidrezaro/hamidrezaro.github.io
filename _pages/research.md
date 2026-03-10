---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Robotic Surgery

My research in robotic surgery focuses on making teleoperated surgical systems safer, more reliable, and more useful for real-world deployment. I work at the intersection of dependable systems, multimodal machine learning, and surgical robotics to understand surgical activity in real time, collect informative data without relying on proprietary robot interfaces, and maintain safe behavior when network conditions degrade.

This research spans three connected themes: multimodal perception for surgical activity recognition and prediction, platform-agnostic sensing and dataset creation for robot-assisted surgery, and activity-aware recovery strategies for telesurgery under packet loss, delay, and communication failures.

### Papers in this area

- [Multimodal Transformers for Real-Time Surgical Activity Prediction]({{ '/publication/multimodal-transformers-real-time-surgical-activity-prediction' | relative_url }}) studies how kinematic, video, and contextual features can be fused for real-time gesture and trajectory prediction in robot-assisted surgery.
- [A Comprehensive Analysis of the Effects of Network Quality of Service on Robotic Telesurgery]({{ '/publication/network-qos-effects-robotic-telesurgery' | relative_url }}) introduces NetFI and analyzes how packet loss, delay, and communication loss affect telesurgical performance, workload, and safety at both task and motion-primitive levels.
- [MiDAS: A Multimodal Data Acquisition System and Dataset for Robot-Assisted Minimally Invasive Surgery]({{ '/publication/midas-multimodal-data-acquisition-system' | relative_url }}) presents an open, platform-agnostic sensing and data collection framework for capturing synchronized multimodal robotic surgery data without proprietary robot access.
- [Activity-Aware Recovery from Network Communication Loss in Teleoperated Robotic Surgery]({{ '/publication/activity-aware-recovery-teleoperated-robotic-surgery' | relative_url }}) proposes a dual-mode recovery framework that combines short-horizon prediction with autonomous recovery to keep telesurgical actions safe during communication disruptions.
