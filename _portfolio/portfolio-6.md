---
title: "Master's thesis — Peg-in-hole assembly with four control modes"
excerpt: "Innopolis University · KUKA LBR iiwa; vision, haptics, shared autonomy, and learning from demonstration."
collection: portfolio
categories:
  - master
date: 2022-07-01
header:
  teaser: https://img.youtube.com/vi/vaFsLzGQ1M8/hqdefault.jpg
permalink: /portfolio/portfolio-6/
redirect_from:
  - /portfolio/portfolio-6.html
---

<div class="video-embed">
<iframe src="https://www.youtube.com/embed/vaFsLzGQ1M8" title="Master thesis peg-in-hole assembly demo" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<p class="project-downloads">
  <a href="/files/mostafa-othman-master-thesis-defense-2022.pdf" class="btn btn--primary"><i class="fas fa-file-pdf" aria-hidden="true"></i> Thesis defence presentation (PDF, 2022)</a>
</p>

## Context

Master's thesis, Innopolis University (Dec 2021 – Jul 2022). Builds on bilateral teleoperation, VR interfaces, and peg-in-hole modules on the same robot.

## Problem

Inserting a cylindrical peg into a hole with clearance at or below the robot's positioning accuracy — a standard benchmark where pure position control fails without contact sensing or human guidance.

## Approach

Implemented and compared **four control strategies** on a **KUKA LBR iiwa** (ROS):

1. **Full autonomy** — vision-guided pick and hybrid position/force assembly ([IEEE NIR 2021 paper](/publication/2021-08-26-robotic-pick-and-assembly/))
2. **Bilateral teleoperation** — Touch haptic device with endeffector force feedback
3. **Shared autonomy** — operator guidance with automated compliance
4. **Learning from demonstration** — imitation-based insertion

Also integrated computer vision for part localisation, a unified hardware software stack, and user studies (design of experiments + survey).

## Outcome

Reliable assembly under tight clearance; bilateral and shared modes improved operator performance vs. position-only control. Presented at thesis defence.

## Stack

ROS · Python · C++ · Computer vision · Haptics · Control systems · KUKA Sunrise

## Documents & links

- **[Thesis defence presentation (PDF)](/files/mostafa-othman-master-thesis-defense-2022.pdf)** — Innopolis University, Jul 2022
- [IEEE NIR 2021 publication](/publication/2021-08-26-robotic-pick-and-assembly/) — related pick-and-assembly work
- [Demo (YouTube)](https://www.youtube.com/watch?v=vaFsLzGQ1M8)
- [MasterThesisWork (GitHub)](https://github.com/mostafa-metwaly/MasterThesisWork) — code and supplementary materials
