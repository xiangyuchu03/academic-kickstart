
---
title: One paper is accepted by IEEE TCST. 
subtitle: "Opposite Treatment on Null Space: A Unified Control Framework for a Class of Underactuated Robotic Systems with Null Space Avoidance"

# Summary for listings and search engines
summary: "Opposite Treatment on Null Space: A Unified Control Framework for a Class of Underactuated Robotic Systems with Null Space Avoidance by Xiangyu Chu, Chun Ho Lo, Tommaso Proietti, Conor J Walsh, and Kwok Wai Samuel Au (10.1109/TCST.2022.3171914)"

# Link this post with a project
projects: []

# Date published
date: "2022-04-18T00:00:00Z"

# Date updated
lastmod: "2022-04-18T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ""
  placement: 2
  preview_only: false

authors:
# - admin
# - 吳恩達

tags:
# - Academic
# - 开源

categories:
# - Demo
# - 教程
---

## Overview
Design of feedback control for Underactuated Robotic Systems (URSs) is often complex and non-intuitive due to the inherent incapability of generating arbitrary velocities or accelerations at each moment. Researchers have designed various controllers, however, there are few unified intuitive feedback stabilization controllers for a wide range of URSs.  In this paper, we propose a real-time and unified control framework for a class of URSs with three states and two inputs based on the intuition of avoiding null space. To control diverse URSs, unlike transforming them to canonical forms, we approach them from an inverse perspective based on a Jacobian-like mapping matrix and disclose a fundamental issue, null space attraction which fails all Jacobian-based standard kinematics control. An opposite treatment on null space, avoiding null space is applied to oppose null space attraction, allowing the standard kinematics controllers to keep control authority. 
Overall, the proposed control framework consisting of a standard kinematics controller and a null space avoidance controller can fundamentally solve point-to-point stabilization for the class of driftless URSs and also render $\Delta$-neighbourhood stabilization for URSs with a non-vanishing and constant drift.

This is the first paper to build theoretical fundation for Null Space Avoidance (NSA). The application of NSA will come soon.




