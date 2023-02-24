---
layout: page
title: movement patterns 
description: 
img: 
importance: 2
---

Movement patterns provide behaviors for robot motion. Basic movement pattern provide standard behavior for robot motion while combined movement patterns combine several basic patterns (movement and voting pattern) to create more complex behaviors. 

ROS2swarm provides the following basic movement patterns: 

* attraction: robots group (based on an attractive potential field) 
* aggregation: robots group (FSM-based approach)
* drive: robots drive straight forward
* dispersion: robots distribute themselves in space (based on a repulsive potential field)
* minimalist flocking: collective motion, implementation based on [Moeslinger et al.](https://link.springer.com/chapter/10.1007/978-3-642-21314-4_47)
* random walk: robots alternate between driving straight forward and turning 

The package contains the following combined movement patterns: 

* discussed dispersion: robots execute the majority rule to determine the minimum distance they want to keep to each other and disperse accordingly 
