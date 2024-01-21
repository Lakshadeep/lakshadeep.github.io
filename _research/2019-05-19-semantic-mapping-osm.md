---
title: "Semantic world modelling and indoor navigation using OpenStreetMap"
excerpt: "We explored how digital navigation maps such as OpenStreetMap can be used for indoor robot navigation"
collection: research
icon_url: '/images/osm-icra19.jpeg'
hashtags: "#semantic world model #OpenStreetMap"
tags:
  - Semantic World Model
  - OpenStreetMap
  - Indoor Robot Navigation
---
<b><i>Abstract</i></b>
In this work a graph-based, semantic mapping approach for indoor robotics applications is presented, which is extending OpenStreetMap (OSM) with robotic-specific, semantic, topological, and geometrical information. Models are introduced for basic indoor structures such as walls, doors, corridors, elevators, etc. The architectural principles support composition with additional domain and application-specific knowledge. As an example, a model for an area is introduced, and it is explained how this can be used in navigation. A key advantage of the proposed graph-based map representation is that it allows exploiting the hierarchical structure of the graphs. Finally, the compatibility of the approach with existing, grid-based motion planning algorithms is shown.

<!-- <img src='/images/icra19-preview.jpeg'> -->

See our [ICRA 2019 paper](/publication/2019-05-20-icra2019) for more details:
[Download paper](https://lirias.kuleuven.be/retrieve/536321)

This research was funded by the <b>European Unions Horizon 2020 ROPOD project</b>.

Here is the video demonstrating the use of proposed approach for multi-floor cart transportation usecase in the <b>ROPOD</b> project:

<iframe width="560" height="315" src="https://www.youtube.com/embed/aBvui9Fne4s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<b><i></i></b>

<b><i>Semantic navigation - proof of concept</i></b>

Semantic navigation exploits the knowledge in the semantic map to select and configure perception and motion control algorithms and effectively turns the localization and navigation task into a sequence of perception and control problems. A solution for each individual perception and control problem is selected from a set of software components. The assumptions and outputs of each componet are continuously momitored to determine the transitions to new components.

<iframe width="560" height="315" src="https://www.youtube.com/embed/zrewX6l_O8Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>