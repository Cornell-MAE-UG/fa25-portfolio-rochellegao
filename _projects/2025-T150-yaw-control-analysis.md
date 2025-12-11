---
layout: project
title: Analysis of the BAE/Malloy T-150 Heavy Lift UAS Yaw Control System Dynamics
description: 
technologies: [MATLAB]
image:
---


In this analysis, my group is studying the yaw control of the BAE/Malloy T-150 heavy-lift unmanned aerial system (UAS). Since flight dynamics are naturally nonlinear, we first linearized the equations of motion for steady, standard, flight conditions. We aimed to maximize the stability around a desired yaw angle, while maintaining constant altitude above the ground and rejecting disturbances. We studied the dynamics surrounding this system based on the inertial measurement unit (IMU), developed the relevant ODEs and thus the transfer functions, generated the block diagram for our system, and then implemented PD control. After the controller was implemented, we used Bode plot analysis in order to further understand the system behavior of different configurations of payloads. Our analysis does not consider the GPS navigation system, pitot-static system and other pressure-based instruments, and other electronic sensors.

A more detailed report of the analysis is linked in this google document:
https://docs.google.com/document/d/1xLOTM-HIjpx8at6oFZeHuxVcsUtd9dP8V8Q2l2OePzo/edit?tab=t.0