---
date: "2024-02-28"
tags:
- In-hand Manipulation
- Prototyping
- Mechanical-Design
title: Acti-V-Link Gripper
url_video: https://www.youtube.com/watch?v=d8GOwXEKnTc&feature=youtu.be
---
**Intelligent Grasping and In-Hand Manipulation** (Final Year Project)
Overview: The intelligent grasping project successfully addressed grasping location detection for non-standard objects, but further development was required in terms of post-grasp dexterity. The ability for a robot to manipulate objects post-grasp remains a critical challenge in robotic manipulation, a challenge I chose to address for my final year project on In-Hand Manipulation.

**Design and Implementation:**
**Mechanical Design:**
We identified that traditional thread-driven underactuated grippers often lacked sufficient grasping force. To resolve this, we developed a four-bar linkage mechanism with an active belt system, enabling enhanced manipulation capabilities. The active belt system was innovatively driven by a single N20 micro motor, controlling both links in a finger, compared to conventional designs that use separate motors for each link.

**Actuation and Control:**
The active belt mechanism, powered by a spur and worm drive, was coupled with a Dynamixel servo motor to centralize control over the gripper’s finger movements. This allowed for precise in-hand manipulation of objects with varying geometries. The mechanically underactuated design with an active surface enabled both secure grasping and intricate manipulation.

**Key Innovations:**
Single-motor-driven active belt system for compact and efficient control of finger movement.
Spur and worm mechanism for centralized control over multiple finger segments, reducing mechanical complexity while maintaining high dexterity.
Integration of a Dynamixel servo for robust control, allowing for smooth and adaptive manipulation of different objects.

<!--more-->
