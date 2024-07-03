---
title: "BaSeNET: A Learning-based Mobile Manipulator Base Pose Sequence Planning for Pickup Tasks"
collection: publications
permalink: /publication/2024-06-30-iros
excerpt: ''
date: 2024-06-30
venue: 'IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
paperurl: ''
citation: 'Naik, L., Kalkan, S., Sørensen S.L., Kjærgaard M.B., & Krüger, N. (Accepted). Basenet: A learning-based mobile manipulator base pose sequence planning for pickup tasks. IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
authors: '<b>Naik, L.</b>, Kalkan, S., Sørensen S.L., Kjærgaard M.B., & Krüger, N.'
type: 'Proceedings Article'
---

[Pre-print](https://portal.findresearcher.sdu.dk/files/253491726/RAL24-pre-grasp-approaching.pdf)

<b>Abstract:</b>
In many applications, a mobile manipulator robot is required to grasp a set of objects distributed in space.
This may not be feasible from a single base pose and the robot must plan the sequence of base poses for grasping all objects, minimizing the total navigation and grasping time. This is a Combinatorial Optimization problem that can be solved using exact methods, which provide optimal solutions but are computationally expensive, or approximate methods, which offer computationally efficient but sub-optimal solutions. Recent studies have shown that learning-based methods can solve Combinatorial Optimization problems, providing nearoptimal and computationally efficient solutions.

In this work, we present BASENET - a learning-based approach to plan the sequence of base poses for the robot to grasp all the objects in the scene. We propose a Reinforcement Learning based solution that learns the base poses for grasping individual objects and the sequence in which the objects should be grasped to minimize the total navigation and grasping costs using Layered Learning. As the problem has a varying number of states and actions, we represent states and actions as a graph and use Graph Neural Networks for learning. We show that the proposed method can produce comparable solutions to exact and approximate methods with significantly less computation time.

<b>Code: [Github link](https://github.com/Lakshadeep/basenet)</b>


<b>Recommended citation:</b>
L. Naik, S. Kalkan, S. L. Sørensen, M. B. Kjærgaard, and N. Krüger, “Basenet: A learning-based mobile manipulator base pose sequence planning for pickup tasks,” in 2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) (Accepted), 2024.

