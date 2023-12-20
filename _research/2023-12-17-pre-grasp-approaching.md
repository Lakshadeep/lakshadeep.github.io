---
title: "Pre-grasp approaching on mobile robots: a pre-active layered approach"
excerpt: "We propose a pre-active approach for determining the base pose and pre-grasp manipulator configuration to improve the time efficiency of MM."
collection: research
redirect_from:
  - /pgamr/
---

In Mobile Manipulation (MM), navigation and manipulation are generally solved as subsequent disjoint tasks. Combined optimization of navigation and manipulation costs can improve the time efficiency of MM. However, this is challenging as precise object pose estimates, which are necessary for such combined optimization, are often not available until the later stages of MM. Moreover, optimizing navigation and manipulation costs with conventional planning methods using uncertain object pose estimates can lead to failures and hence requires re-planning. Hence, in the presence of object pose uncertainty, pre-active approaches are preferred.  

We propose a pre-active approach for determining the base pose and pre-grasp manipulator configuration to improve the time efficiency of MM. We devise a Reinforcement Learning (RL) based solution that learns suitable base poses for grasping and pre-grasp manipulator configurations using layered learning that guides exploration and enables sample-efficient learning. Further, we accelerate learning of pre-grasp manipulator configurations by providing dense rewards using a predictor network trained on previously learned base poses for grasping. 

<iframe width="400" height="240" src="https://www.youtube.com/embed/e1W-owaG_I4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>
<b>[Github link](https://github.com/Lakshadeep/pre-grasp-approaching)</b> (Coming soon)


