# Pick and Place Robot arm  Simulation 

This README.md file is a overview of a pick-and-place robot arm for stacking application developed in ROS2 using Moveit2, in collaboration with [Mr. Lentin Joseph.](https://www.linkedin.com/in/lentinjoseph/).

Here, I shall go over the approach taken and briefly discuss how one can implement the same. Unfortunately, this work is not open-source, but I am working on a similar implementation for the same and it will roll out soon!
Here are the steps:

So the goal of the project was to develop the code-base for a robot arm that could be used in warehouse automation for [palletizing boxes/cartons](https://www.youtube.com/watch?v=7U1-X5ogsKA).

The functionality was such that the user could simply input the number of boxes per layer, pattern (if any)
in which they wanted to place the boxes, the dimension of the pallet, and et. voila! The robot would do it.

One great feature of Moveit2 is it's [Moveit Task Constructor](moveit.picknik.ai/humble/doc/tutorials/pick_and_place_with_moveit_task_constructor/pick_and_place_with_moveit_task_constructor.html) that comes handy in exactly these tasks.

Checkout a glimpse of what we implemented.

![Pick place Demo](https://raw.githubusercontent.com/tejasps28/ROS2-Projects/main/pick_place_arm/img/4x4_pnp_cropped.gif)


## Future Work

Happy Exploring!
