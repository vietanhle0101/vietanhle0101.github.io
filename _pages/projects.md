---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## Adaptive Sampling for Mobile Robotic Sensor Networks

This project is a collaboration with Dr. Linh Nguyen from Australia Federation University. In this project, we develop efficient adaptive sampling strategies for resource-constrained Mobile Robotic Sensor Network for monitoring a spatial phenomenon based on Gaussian Process. The adaptive sampling problem can be formulated as minimizing the negative log determinant of a predicted covariance matrix, which is a non-convex and highly complex function. Moreover, the constraints on robot mobility such as nonholonomic dynamics and inter-robot collision avoidance are taken into consideration. Some optimization techniques like Proximal ADMM and Successive Convexification Programming can be applied to efficiently solve this problem in continuous domain.

## Gaussian Process based Distributed Model Predictive Control for Multi-agent Systems

This project aims to develop distributed algorithms for data-driven Distributed Model Predictive Control for multi-agent control systems, where the agents’ dynamics are modeled by Gaussian Processes (GPs). We employ the linearized Gaussian Process (linGP) concept, to sequentially approximate the stochastic latent processes of the GP models in a Sequential Convex Programming (SCP) framework, leading to a convex linGP-DMPC subproblem, which is solved cooperatively by the agents with the ADMM algorithm. The resulting distributed algorithm, called linGP-SCP-ADMM, can solve non-convex GP-DMPC for multi-agent systems effectively since the data and computation are distributed among the agents.
