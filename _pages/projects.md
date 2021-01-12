---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## Gaussian Process based  Model Predictive Control
<!-- ![](../images/ccta.png) -->

This project aims to enhance the performance of Model Predictive Control (MPC) by using Gaussian Processes (GPs) to learn system dynamics. Our [CCTA 2020 paper](https://ieeexplore.ieee.org/abstract/document/9206390) considered a Distributed Model Predictive Control (DMPC) problem for multi-agent coordination, where Gaussian Processes were utilized to learn agent's dynamics and an algorithm, called linGP-SCP-ADMM that combines the Sequential Convex Programming and the distributed ADMM algorithm, was developed to solve the non-convex GP-DMPC problem effectively. More interestingly, there is a connection between the adaptive sampling/sensor placement problem in Mobile Sensor Network (see the project below) and the active learning problem in Learning-based MPC. A manuscript on this idea has been submitted to CCTA 2021.

## Adaptive Sampling for Mobile Robotic Sensor Networks
<!-- ![](../images/mrsn.png) -->

This project is a collaboration with Dr. Linh Nguyen from Australia Federation University. In this project, we develop efficient adaptive sampling strategies for a resource-constrained Mobile Robotic Sensor Network for monitoring a spatial phenomenon based on Gaussian Process. The adaptive sampling problem can be formulated as minimizing the negative log determinant of a predicted covariance matrix, which is a non-convex and highly complex function. Moreover, the constraints on robot mobility such as nonholonomic dynamics and inter-robot collision avoidance are taken into consideration. A manuscript has been submitted to IEEE Sensor Journal. This temporary [poster](../files/MRSN_poster.pdf) may be helpful to get the overall idea.

## Modeling and Control of Overhead Crane/Ship-mounted Crane

This research and experiment were conducted when I was an undergraduate research intern at School of Mechanical Engineering, Vietnam Maritime University. My duty includes designing anti-swing control algorithms for uncertain overhead crane/ship-mounted crane using sliding mode approach and Radial Basis Function (RBF) Neural Networks and implementing them on NI-MyRIO microcontroller. Details can be found in our papers ([1](https://www.sciencedirect.com/science/article/abs/pii/S0888327018302322), [2](https://link.springer.com/article/10.1007/s11633-019-1174-y)) and [video](https://www.youtube.com/watch?v=ZlF37IZh89Q).
