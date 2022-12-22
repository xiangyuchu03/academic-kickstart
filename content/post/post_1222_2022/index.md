
---
title: One paper is accepted by IEEE TMech. 
subtitle: "Feedback Control for Collision-Free  Nonholonomic Vehicle Navigation on SE(2) with Null Space Circumvention"

# Summary for listings and search engines
summary: "Feedback Control for Collision-Free  Nonholonomic Vehicle Navigation on SE(2) with Null Space Circumvention by Xiangyu Chu, Raymond Ng, Hesheng Wang, and Kwok Wai Samuel Au (10.1109/TMECH.2022.3186174)"

# Link this post with a project
projects: []

# Date published
date: "2022-06-18T00:00:00Z"

# Date updated
lastmod: "2022-06-18T00:00:00Z"

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
In this paper, we present a novel feedback controller for collision-free navigation of a class of nonholonomic vehicles based on navigation functions in convex environment. This controller utilizes a high-level principle - null space circumvention in nonholonomic navigation control, allowing us to involve different vehicle kinematics and navigation functions with respect to the task and environment. For a single vehicle, we have proved that the controller can steer it to the target on $\text{SE(2)}$ while avoiding collision from almost all initial states. The controller can also close the gap between holonomic vehicle navigation and nonholonomic vehicle navigation, allowing the navigation functions created for holonomic vehicles to be used for nonholonomic vehicles. Furthermore, we extend the controller to multi-vehicle formation control. Within this task, our controller shows generality without much modification except for updating the gradient of the chosen navigation functions. Simulation and experimental results demonstrate that the proposed controllers can achieve collision-free navigation for a single vehicle and multiple vehicles.

This is an application paper of using Null Space Avoidance (NSA) theory. Next Application would be integrating NSA into numerical methods, such as QP and MPC.





