---
title: "Multimodal Transformers for Real-Time Surgical Activity Prediction"
collection: publications
permalink: /publication/multimodal-transformers-real-time-surgical-activity-prediction
excerpt: "This paper introduces a multimodal transformer that fuses kinematic and video data for real-time surgical gesture and trajectory prediction, improving accuracy while staying fast enough for deployment."
date: 2024-05-13
venue: "IEEE International Conference on Robotics and Automation (ICRA)"
paperurl: /files/icra2024.pdf
header:
  teaser: /files/icra2024.png
---
<img src="{{ '/files/icra2024.png' | relative_url }}" alt="Architecture for multimodal surgical activity prediction" style="max-width: 100%; height: auto;" />

This paper presents a multimodal transformer architecture for real-time recognition and prediction of surgical gestures and trajectories from short windows of kinematic and video data. Through an ablation study across different sensing modalities and feature representations, the work shows that combining robot kinematics with spatial and contextual video cues improves predictive accuracy while preserving real-time performance.

Evaluated on the JIGSAWS dataset, the model outperforms prior gesture prediction approaches and processes one-second input windows in only a few milliseconds, making it suitable for applications such as safety monitoring, autonomy, and intelligent teleoperation assistance in robot-assisted surgery.

[Download paper here]({{ page.paperurl | relative_url }})
