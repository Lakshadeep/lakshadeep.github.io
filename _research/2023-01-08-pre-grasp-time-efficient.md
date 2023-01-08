---
title: "Pre-grasp planning for time efficient grasping on mobile robots"
excerpt: "We are addressing the problem of pre-grasp planning as the robot approaches the object for grasping"
collection: research
---

We are addressing the problem of pre-grasp planning as the robot approaches the object by coupling base and end-effector motion to improve visual object pose estimates and determine pre-grasp mobile base and end-effector configuration that minimizes the grasping time. 

<b>Learning to approach for grasping with visual constraints on symmetric platform </b>


<iframe width="560" height="315" src="https://www.youtube.com/embed/uMpFqsgZfJU?autoplay=1&amp;mute=1&amp;loop=1&amp;playlist=uMpFqsgZfJU&amp;controls=0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"></iframe>

<br>
<b>Learning to approach for grasping with visual constraints on asymmetric ER platform </b>

<iframe width="560" height="315" src="https://www.youtube.com/embed/uW4l92JNEzk?autoplay=1&amp;mute=1&amp;loop=1&amp;playlist=uW4l92JNEzk&amp;controls=0"  frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"></iframe>

<br>
In both cases, the robot is trying to learn to reach within the grasping distance of the object while satisfying the visual constraints during approaching. This includes keeping the object in the field of view so that the 6D object pose estimate can be tracked. In the case of a symmetric robot, it learns a policy to approach the object straight as when its front is facing the table, the object is within the grasping distance due to the positioning of the arm base at the center of the mobile base. In the case of the asymmetric robot, following the same policy as the symmetric robot is not enough as when the robot's front is facing the table the object is not within the grasping distance of the arm. Hence it tries to approach from the side and uses its end-effector motion to keep the object in the field of view during the approach (still learning!!). We are currently trying to optimize it further and then learn a pre-grasp end-effector configuration that minimizes the grasp execution time.



