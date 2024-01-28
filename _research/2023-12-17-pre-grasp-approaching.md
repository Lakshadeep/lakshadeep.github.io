---
title: "Pre-grasp approaching on mobile robots"
excerpt: "In this research, we explored the use of a pre-active approach to determine a suitable base pose and pre-grasp manipulator configuration for grasping on mobile robots."
collection: research
redirect_from:
  - /pgamr/
hashtags: "#reinforcement learning #mobile manipulation"
icon_url: '/images/ral-pre-grasp.jpg'
tags:
  - Reinforcement Learning
  - Mobile Manipulation
---

<b>Addressed Problem:</b>
In Mobile Manipulation (MM), navigation and manipulation are generally solved as subsequent disjoint tasks. Combined optimization of navigation and manipulation costs can improve the time efficiency of MM. However, this is challenging as precise object pose estimates, which are necessary for such combined optimization, are often not available until the later stages of MM. Moreover, optimizing navigation and manipulation costs with conventional planning methods using uncertain object pose estimates can lead to failures and hence requires re-planning. Hence, in the presence of object pose uncertainty, pre-active approaches are preferred.  

<b>Proposed solution:</b>
We propose a pre-active approach for determining the base pose and pre-grasp manipulator configuration to improve the time efficiency of MM. We devise a Reinforcement Learning (RL) based solution that learns suitable base poses for grasping and pre-grasp manipulator configurations using layered learning that guides exploration and enables sample-efficient learning. Further, we accelerate learning of pre-grasp manipulator configurations by providing dense rewards using a predictor network trained on previously learned base poses for grasping. 

<b>See our [RA-L paper](/publication/2024-01-08-ral) for more details. [Download pre-print](https://portal.findresearcher.sdu.dk/files/253491726/RAL24-pre-grasp-approaching.pdf)</b>

<b>Code: [Github link](https://github.com/Lakshadeep/pre-grasp-approaching)</b>

<b>Supplementary Video for the RAL paper:</b>

<iframe width="400" height="240" src="https://www.youtube.com/embed/e1W-owaG_I4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>

This research was supported by the <b>Innovation Fund Denmark</b> in the context of the <b>FacilityCobot</b> project.

