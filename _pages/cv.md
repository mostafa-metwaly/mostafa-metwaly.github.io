---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<iframe
    src="https://mostafa-metwaly.github.io/files/MostafaOthman_CV.pdf"
    frameBorder="0"
    scrolling="auto"
    height="950"
    width="100%"
></iframe>

{% include base_path %}

## [Download CV (PDF)](https://mostafa-metwaly.github.io/files/MostafaOthman_CV.pdf)

*Upload the latest PDF to `files/MostafaOthman_CV.pdf` when you export from Overleaf.*

### Education

* **M.Sc.** Robotics and Computer Vision — Innopolis University, 2022
* **B.Sc.** Mechatronics Engineering — Nile University, 2020

### Work experience

* **Robotics Field Engineer** — Wayve Technologies, Tokyo, Japan (Nov 2025 – present)
  * Commission autonomous vehicles; validate OS and model releases; debug CAN/DBW and ECU integration; on-road safety and incident response

* **Robotics Field Engineer** — Rapyuta Robotics, Tokyo, Japan (Dec 2022 – Oct 2025)
  * Deployed and supported AMR and autonomous forklift fleets across 8 production sites
  * Automation and simulation for pre-deployment testing; on-robot LTE architecture for remote support

* **Research Assistant** — Innopolis University (Summer 2021)
  * Teleoperation of cable-driven robot with Touch haptic device (Prof. Igor Gapanov)

### Skills

* **Robotics:** ROS, computer vision, motion planning, control systems, state estimation, teleoperation, haptics
* **Languages:** Python, C++, C#, MATLAB, Go
* **Tools:** Linux, Docker, Git, Unity, Grafana, Foxglove, Simulink, SOLIDWORKS

### Publications

<ul>{% for post in site.publications %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
