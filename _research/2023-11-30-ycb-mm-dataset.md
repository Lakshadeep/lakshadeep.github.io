---
title: "Multi-view YCB object pose tracking dataset for Mobile Manipulation (MY-MM)"
excerpt: "We released a Multi-view YCB object pose tracking dataset for Mobile Manipulation (MY-MM) with views of the objects from the robot's eye-in-hand and external cameras in the environment."
collection: research
---

<b>Download link and usage details coming soon. </b>


Today, mobile manipulation is performed in a sequential manner—first navigation and then manipulation—since accurate object pose estimates, crucial for planning manipulation, are only available when the robot is in close proximity to objects. If accurate object pose estimates can be made available while the robot is still navigating towards the object, it can already begin making manipulation decisions. This has the potential to enhance the time efficiency of mobile manipulation. Hence, it is necessary to benchmark how well object poses can be estimated while the robot is still navigating towards the object.
<br>


<iframe src="https://www.youtube.com/embed/h5z4iLnnCkk?autoplay=1&amp;mute=1&amp;loop=1&amp;playlist=h5z4iLnnCkk&amp;controls=0"></iframe>

<br>
As the mobile robot approaches the object for grasping using its base and arm motion, initially, the robot's "eye-in-hand" camera will have a very limited view of the object, and this view will improve as the robot moves closer to the object. On the other hand, static external cameras will always maintain the same view of the object. Additionally, there is a possibility that as the robot approaches the object, it may become occluded by other objects in the scene. In such cases, the robot is expected to utilize its motion to obtain better views of the object.
<br>


<iframe src="https://www.youtube.com/embed/Tls1xaX39j0?autoplay=1&amp;mute=1&amp;loop=1&amp;playlist=Tls1xaX39j0&amp;controls=0"></iframe>

<br>
Existing real-world object pose estimation benchmark datasets, such as the YCB Video dataset, primarily consist of short single-camera video sequences without significant changes in the object's view. The camera is positioned very close to the objects, simulating scenarios where the robot is already in close proximity to the object for grasping. We address this gap with a "Multi-view YCB object pose tracking dataset for Mobile Manipulation" (MY-MM).
<br>

<iframe src="https://www.youtube.com/embed/J9P8sZl5gvo?autoplay=1&amp;mute=1&amp;loop=1&amp;playlist=J9P8sZl5gvo&amp;controls=0"></iframe>

<br>
The dataset consists of 100 sequences featuring 10 different YCB objects with distinct geometries and textures. For each video sequence, we provide the 6D pose of the object of interest in the robot camera frame, views of the scene from two external cameras, the transformations between all cameras at each time step, and intrinsic calibration for all the cameras. Each object has approximately 10 sequences with ground truth poses.
<br>


<iframe src="https://www.youtube.com/embed/K0-RsRDUglI?autoplay=1&amp;mute=1&amp;loop=1&amp;playlist=K0-RsRDUglI&amp;controls=0"></iframe>


