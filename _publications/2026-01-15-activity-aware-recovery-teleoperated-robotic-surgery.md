---
title: "Activity-Aware Recovery from Network Communication Loss in Teleoperated Robotic Surgery"
collection: publications
permalink: /publication/activity-aware-recovery-teleoperated-robotic-surgery
excerpt: "This paper proposes a dual-mode recovery framework that predicts surgeon commands during short disruptions and autonomously completes the current subtask during prolonged communication loss."
date: 2026-01-15
venue: "IEEE Transactions on Medical Robotics and Bionics"
publication_label: "Submitted to"
paperurl: /files/tmrb.pdf
header:
  teaser: /files/tmrb.png
---
<img src="{{ '/files/tmrb.png' | relative_url }}" alt="Activity-aware recovery architecture for teleoperated robotic surgery" style="max-width: 100%; height: auto;" />

This paper addresses the safety risks of packet drops and prolonged communication failures in teleoperated robotic surgery. It introduces an activity-aware shared-control framework that combines two recovery modes: a context-aware Transformer for short-term prediction of surgeon commands and a library of Dynamic Movement Primitives for long-term autonomous completion of the current surgical subtask.

Using surgical activity recognition and task knowledge to guide recovery, the framework reduces trajectory deviation under severe packet loss and improves end-to-end recovery performance compared with using filtering or a single recovery strategy alone. The result is a more fault-tolerant approach to maintaining safe telesurgical behavior during diverse network disruptions.

[Download paper here]({{ page.paperurl | relative_url }})
