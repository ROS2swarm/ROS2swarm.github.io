---
layout: about
title: about
permalink: /
subtitle: 

profile:
  align:
  image: 
  image_circular: false # crops the image to make it circular
  address: 

news: true  # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

ROS2swarm is a ROS 2 package intended to simplify and promote the use of ROS 2 in swarm robotics research, industry, and education. It is an easy-to-extend framework for and library of swarm behaviors.

ROS2swarm provides movement patterns for robot motion and voting patterns for collective decision-making. We distinguish between basic patterns that implement primitive swarm behaviors and combined patterns that implement more complex behaviors. Parameter files allow the adjustment of patterns for different robot platforms and scenarios. In addition, we included a hardware protection layer to prevent hardware damage.

The package is available for Dashing and Foxy since our main development platform is the TurtleBot3 Waffle Pi. Furthermore, we provide out-of-the-box support for the TurtleBot3 Burger and the Jackal UGV (using the ros1_bridge 5 package). We also provide simulations in Gazebo for all three platforms to simplify development. New platforms that provide distance measurements in a LaserScan message and are controlled by linear velocities along the x-axis and rotational velocities around the z-axis can easily be added.

Currently, we are working on integrating support for robots with less sophisticated sensor setups, such as the Thymio II, enabling local communication, and adding more swarm behaviors.

Please contact us if you want to contribute or if you have suggestions for new features. 
