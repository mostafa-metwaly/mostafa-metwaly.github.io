---
title: "Cable-driven robot teleoperation with haptic master"
excerpt: "Innopolis University · 10×7 m cable robot; Touch haptic device; websockets; Omron PLC; Go kinematics."
collection: portfolio
categories:
  - master
date: 2021-07-01
header:
  teaser: https://img.youtube.com/vi/IGJtQsirpvE/hqdefault.jpg
permalink: /portfolio/portfolio-2/
redirect_from:
  - /portfolio/portfolio-2.html
---

<div class="video-embed">
<iframe src="https://www.youtube.com/embed/IGJtQsirpvE" title="Cable-driven robot haptic teleoperation" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## Context

Research internship, Innopolis University Intelligent Robotic Systems Lab (May – Jul 2021). Supervisor: Prof. Igor Gapanov.

## Problem

Teleoperate a large **cable-driven parallel robot** (~10×7 m workspace) with intuitive control and coordinated motor commands across multiple winches.

## Approach

- Bilateral **websocket** communication between Touch haptic device (C++) and robot control stack
- Velocity control modes for smooth end-effector motion
- **Omron PLC** commanding motor drivers
- **Go** services for kinematics and command routing

## Outcome

Operator teleoperation of the full-scale cable robot via the haptic master — integration of haptics, industrial PLCs, and non-standard manipulator kinematics.

## Stack

Go · C++ · PLC · Websockets · Haptics · Motion planning

## Links

- [Demo (YouTube)](https://www.youtube.com/watch?v=IGJtQsirpvE)
- [GitHub](https://github.com/mostafa-metwaly/Cable-driven-robot)
