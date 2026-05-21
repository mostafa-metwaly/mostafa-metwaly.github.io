---
title: "Haptic peg-in-hole with impedance control (KUKA iiwa)"
excerpt: "Innopolis University · teleoperation with force feedback and impedance compliance for tight-clearance insertion."
collection: portfolio
categories:
  - master
date: 2022-03-01
header:
  teaser: https://img.youtube.com/vi/MwppmW9Z21s/hqdefault.jpg
permalink: /portfolio/portfolio-5/
redirect_from:
  - /portfolio/portfolio-5.html
---

<div class="video-embed">
<iframe src="https://www.youtube.com/embed/MwppmW9Z21s" title="Haptic peg-in-hole with impedance control" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## Context

Graduate research module leading into the [master's thesis](/portfolio/portfolio-6/) comparison of four control modes.

## Problem

Stiff position-only teleoperation causes chatter and failed insertion when contact forces spike in tight clearance.

## Approach

- **KUKA iiwa** teleoperated via **Touch** haptic device with force reflection
- **Impedance/compliance** on the robot side for safe yielding during contact

## Outcome

Stable haptic-guided insertion; validated before benchmarking autonomy, shared control, and learning-based modes in the thesis.

## Stack

ROS · Python · Haptics · Impedance control · Motion planning

## Links

- [Demo (YouTube)](https://www.youtube.com/watch?v=MwppmW9Z21s)
- [Computer vision repo](https://github.com/mostafa-metwaly/ComputerVision-Project)
