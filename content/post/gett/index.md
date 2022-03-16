---
title: I defended my PhD dissertation on July 12, 2021. 
subtitle: "Exploiting Null Space for Real-Time and Effective Control of Underactuated Robotic Systems"

# Summary for listings and search engines
summary: "Exploiting Null Space for Real-Time and Effective Control of Underactuated Robotic Systems"

# Link this post with a project
projects: []

# Date published
date: "2021-07-13T00:00:00Z"

# Date updated
lastmod: "2021-07-13T00:00:00Z"

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
Null space is a commonly-used tool in the control of redundant robotic systems,
however, its existence and functionality in Underactuated Robotic Systems
(URSs) have rarely been discussed and were overlooked for a long time. In this
thesis, to the best knowledge, the null space that occurs in URSs is the first
time to be investigated formally and it is shown to be able to provide real-time
and effective control solutions for a large range of URSs, even with constraints.
Although many different methods of controlling URSs, ranging from motion planning
to feedback control, have been explored extensively, designing real-time and
effective control algorithms for (constrained) URSs is still challenging due to 1) a
fundamental obstruction, Brockett’s necessary condition and 2) extra constraints
imposed on states and control inputs apart from nonholonomic constraints.

In this thesis, we approach a real-time and effective paradigm for the control
of (constrained) URSs at two levels: the kinematics-level URSs (KURSs)
and dynamics-level URSs (DURSs). Firstly, we present an inverse perspective
for the unconstrained KURS control, from which a kind of null space that is
often ignored in KURSs is revealed. Then, a novel null space avoidance (NSA)
principle, i.e., avoiding an error vector to fall into the null space and thus keeping
control authority, is proposed to circumvent the fundamental obstruction -
Brockett’s necessary condition. With this principle, an NSA control framework is
designed, especially for a class of 3-state-2-input unconstrained KURSs. Within
the framework, two controllers are constructed with stability and convergence
proofs, including the point-to-point stabilization controller (two versions including
Jacobian pseudoinverse and Jacobian transpose) for the driftless KURSs and the Δ-neighborhood stabilization controller for the drift KURSs. Furthermore,
the extension of the NSA control framework to n-state-(n − 1)-input KURSs
(n ≥ 3) with one-dimensional null space is explored.

Inspired by the NSA principle and its resulting controllers, three methods for
controlling the constrained KURSs are presented. First, an NSA-QP algorithm
is proposed to address KURSs solely with input constraints where the proposed
Jacobian-pseudoinverse-based controller can be integrated with Quadratic Programming
(QP). Second, a feedback navigation controller is proposed to address
KURSs solely with state constraints (e.g., obstacles) where Lyapunov functions
used in the proposed Jacobian-transpose-based controller can be formulated as a
general energy function with a unique global minimum such as navigation functions.
The third is interpreting the NSA principle into performance indices and
constraints for optimization frameworks, such as Trajectory Optimization (TO)
and Model Predictive Control (MPC). For that, state and input constraints can
be included simultaneously. Moreover, an NSA-MPC algorithm is proposed with
the capability of being implemented in hardware.

Beyond the conceptual innovation, attention is paid to apply the NSA control
framework to DURSs with some techniques, such as kinematics reduction
and system decomposition. The joint space control of a planar three-link underactuated
manipulator with a passive first joint and the stabilization of an
underactuated marine vehicle are taken as illustrating examples, respectively.
Except for the null space in KURSs, another kind of null space is also usually
ignored in some DURSs with an inherent first-order nonholonomic constraint (the
mapping matrix of its Pfaffian form has a non-trivial null space). For example,
a planar N-link underactuated manipulator with a passive first joint has such
a constraint originated from angular momentum conservation. The null space
observed in this kind of DURSs is fairly different from that appears in KURSs.
Projecting its original dynamics into the null space can facilitate the constrained
Operational Space Control (OSC) using QP in real time, without involving any
motion planning methods.

Extensive simulation and experimental results have demonstrated the effectiveness
and generality of the proposed methods. Given the success of the initial study, we hope that our explorations provide a starting point to the field to further
study the neglected null space, ultimately inspiring more effective real-time
control solutions for various classes of URSs.




