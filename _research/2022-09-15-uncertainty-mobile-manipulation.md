---
title: "Object pose uncertainty quantification for mobile manipulation"
excerpt: "We propose a method to quantify object pose uncertainty as a reduced set of object poses with predictive confidence, computed from an estimate of the posterior pose distribution."
collection: research
---

<b><i>Abstract</i></b>
<br>

Recent work has shown that object pose distribution can be tracked even when a mobile robot is far from
the object. This can allow the mobile robot to pre-plan grasp while it is still navigating towards the object it intends to grasp. However, the obtained pose distributions are difficult to use for practical robotic applications such as grasp planning due to their large size, unreliable likelihoods, challenges in obtaining a point estimate etc. In this work, we present a method that quantifies object pose uncertainty as a reduced set of object poses with predictive confidence, which is computed from an estimate of the posterior pose distribution. Our method uses temporal consistency and spatial nature of the posterior pose distribution to obtain useful uncertainty quantification for robotic tasks. Our results show that it results in accurate pose estimates when it predicts high confidence and otherwise maintains a compact set of object pose hypotheses that can serve as a simplified pose distribution to enable grasp planning.

<br>
<img src="/images/obj_uncertainty_mobile_manipulation.png" width="500px" alt="Idea">
<br>
<b>(a)</b> Robot camera views, <b>(b)</b> Posterior orientation distribution conditioned over a translation estimate for the "sugar box" object from YCB benchmark, <b>(c)</b> Reduced set of object poses maintained by proposed method at each time step


