---
title: "KUKA iiwa teleoperation in virtual reality"
excerpt: "Innopolis University · ROS, KUKA Sunrise, Unity, Samsung HMD, and Touch haptic feedback."
collection: portfolio
categories:
  - master
date: 2021-11-01
header:
  teaser: https://img.youtube.com/vi/Fn2Nb0Y-_eM/hqdefault.jpg
permalink: /portfolio/portfolio-4/
redirect_from:
  - /portfolio/portfolio-4.html
---

<div class="video-embed">
<iframe src="https://www.youtube.com/embed/Fn2Nb0Y-_eM" title="KUKA iiwa VR teleoperation" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## Context

Graduate laboratory project — immersive teleoperation interface for the KUKA iiwa during the master's programme.

## Problem

2D interfaces hide collision risk and contact state when commanding a manipulator remotely.

## Approach

- ROS bridge to **KUKA Sunrise** (forward/inverse kinematics, 6 DOF)
- **Touch** haptic device for input and force feedback
- **Unity** scene in a **Samsung HMD**
- Real-time coupling between VR, simulation, and hardware

## Outcome

Immersive teleoperation of the real arm with haptic cues — used in later shared-autonomy and user-study work.

## Stack

ROS · Python · Unity · VR · Websockets · Haptics · Motion planning

## Links

- [Demo (YouTube)](https://www.youtube.com/watch?v=Fn2Nb0Y-_eM)
- [GitHub](https://github.com/mostafa-metwaly/Design-and-Controlling-a-VR-system-for-Teleoperation-of-6DOF-Robotic-manipulator)
