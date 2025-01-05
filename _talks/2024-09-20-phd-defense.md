---
title: "Pre-grasp planning for time-efficient and robust mobile manipulation"
collection: talks
type: "PhD defense"
permalink: /talks/2024-09-20-talk-phd-defense
venue: 'University of Southern Denmark'
date: 2024-09-20
location: "Odense, Denmark"
---
<b>Abstract:</b>
In Mobile Manipulation (MM), navigation and manipulation actions are commonly addressed sequentially. The time efficiency of MM can be improved by simultaneously planning pre-grasp manipulation actions while the robot performs the navigation actions. However, planning pre-grasp manipulation actions requires accurate 6D object poses, which are usually available only when the robot is close to and has a clear view of the objects. Further, pre-grasp planning with uncertain poses can lead to failures. This thesis explores how to provide reliable object poses for pre-grasp planning along with their associated uncertainties while the robot is still approaching the objects for grasping, and how to use these pose estimates to plan pre-grasp actions and make informed decisions to enhance the time efficiency and robustness of mobile manipulation.

The first part of this thesis focuses on improving the object pose estimates while the robot approaches the objects for grasping. We develop a multi-view 6D pose distribution tracking framework that provides 6D object pose along with the associated uncertainties. The framework compensates for limited views of the robot camera while approaching by incorporating additional views from the stationary external cameras in the environment. The second part of this thesis focuses on making informed decisions to reduce the risk of failures due to uncertain object pose estimates. We develop a probabilistic inferencing framework to determine if the uncertainty in the object pose estimate is acceptable for successfully executing the action. The framework considers both the estimated uncertainty in the object pose and the acceptable uncertainty for successfully completing the robotic action to determine the likelihood of success. The final part of this thesis focuses on pre-grasp planning to improve the time efficiency of mobile manipulation with online planning. We develop learning-based methods for pre-grasp planning that exploit the inherent hierarchical structure of pre-grasp planning tasks to improve sample efficiency during learning. First, we learn to plan a pre-grasp approaching motion before grasping. Furthermore, we learn to plan the object’s grasp sequence and base poses for grasping.

The main contributions of this thesis include i) the integration of observations from stationary external cameras in the environment with the dynamic robot camera for 6D object pose estimation and associated uncertainty quantification, ii) a demonstration of the use of quantified pose uncertainties to make informed robotic decisions, and iii) sample-efficient learning by exploiting the inherent hierarchical structure of the tasks. With these contributions, we believe this work contributes to enabling time-efficient and robust MM under uncertain pose estimates.


[PhD thesis](https://portal.findresearcher.sdu.dk/en/publications/pre-grasp-planning-for-time-efficient-and-robust-mobile-manipulat)

<!-- [Poster](/files/sdu-christmas2022-poster.pdf) -->