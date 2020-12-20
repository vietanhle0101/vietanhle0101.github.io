---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## Learning based Distributed Model Predictive Control for Multi-agent Systems
<!-- ![](../images/ccta.png) -->

This project aims to develop distributed algorithms for Learning based Distributed Model Predictive Control (DMPC) of multi-agent control systems, where the agents’ dynamics are modeled by a machine learning model. Our [CCTA 2020 paper](https://ieeexplore.ieee.org/abstract/document/9206390) utilized Gaussian Process (GP) to learn system dynamics, and an algorithm, called linGP-SCP-ADMM that combines the Sequential Convex Programming and the distributed ADMM algorithm, was proposed to solve the non-convex GP-DMPC problem effectively.

## Adaptive Sampling for Mobile Robotic Sensor Networks
![](../images/mrsn.png)

This project is a collaboration with Dr. Linh Nguyen from Australia Federation University. In this project, we develop efficient adaptive sampling strategies for a resource-constrained Mobile Robotic Sensor Network for monitoring a spatial phenomenon based on Gaussian Process. The adaptive sampling problem can be formulated as minimizing the negative log determinant of a predicted covariance matrix, which is a non-convex and highly complex function. Moreover, the constraints on robot mobility such as nonholonomic dynamics and inter-robot collision avoidance are taken into consideration. A manuscript has been submitted to IEEE Sensor Journal. More interestingly, there is a connection between the adaptive sampling problem and the optimal experiment design (OED) problem in learning-based control. Let's wait for our work on this idea.

## Modeling and Control of Overhead Crane/Ship-mounted Crane

This research and experiment were conducted when I was an undergraduate research intern at School of Mechanical Engineering, Vietnam Maritime University. My duty includes designing an anti-swing control algorithms for uncertain overhead crane/ship-mounted crane using sliding mode approach and Radial Basis Function (RBF) Neural Networks and implementing it on a microcontroller. Details can be found in our papers ([1](https://www.sciencedirect.com/science/article/abs/pii/S0888327018302322), [2](https://link.springer.com/article/10.1007/s11633-019-1174-y)) and [video](https://www.youtube.com/watch?v=ZlF37IZh89Q).
