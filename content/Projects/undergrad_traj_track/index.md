---
title: "Autonomous System Trajectory Tracking in Unity Engine"
layout: "simple"
date: 2025-05-15
summary: "Undergraduate autonomous system project with trajectory generator, controller, and estimator."
cover:
  image: "/images/control_diagram.svg"
---

As part of my Undergraduate Honors Thesis, I created an autonomous system simulation software framework connecting Python and Unity Engine. Using sockets, I was able to get a spherical physics object in Unity to communicate with Python to send information back and forth so that the sphere could be driven to some desired target coordinate. The figure below shows the autonomous system circuit design, with the blue block signifying execution in Unity and the red blocks signifying execution in Python. 

{{< figure
    src="featured.svg"
    alt="Control System Diagram"
    caption="Control System Diagram"
    >}}