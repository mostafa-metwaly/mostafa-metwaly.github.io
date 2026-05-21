---
title: "Bilateral teleoperation — KUKA iiwa and Touch haptic device"
excerpt: "Innopolis University · Cartesian and joint mapping with endeffector force reflection."
collection: portfolio
categories:
  - master
date: 2021-09-01
header:
  teaser: https://img.youtube.com/vi/veS7uErQFMY/hqdefault.jpg
permalink: /portfolio/portfolio-3/
redirect_from:
  - /portfolio/portfolio-3.html
---

<div class="video-embed">
<iframe src="https://www.youtube.com/embed/veS7uErQFMY?start=1" title="Bilateral KUKA iiwa teleoperation" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## Context

Graduate laboratory project at Innopolis University — precursor to VR teleoperation and peg-in-hole thesis work on the same platform.

## Problem

Unilateral teleoperation gives no force cues during contact tasks; operators cannot feel collisions or insertion resistance.

## Approach

- **Bilateral control** between 3D Systems Touch haptic device and **KUKA iiwa**
- Cartesian and joint-space master–slave mapping
- Force reflection from endeffector to the operator (ROS / C++)

## Outcome

Improved operator awareness and task performance vs. unilateral control; foundation for later peg-in-hole and thesis experiments.

## Stack

ROS · C++ · Haptics · Control systems · KUKA Sunrise

## Links

- [Demo (YouTube)](https://www.youtube.com/watch?v=veS7uErQFMY)
