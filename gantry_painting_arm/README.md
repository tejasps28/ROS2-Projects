# Gantry Arm ROS2 GAzebo Simulation 

This README.md file is a overview of a gantry arm based car painting application developed in simulation using Gazebo, under the mentorship of [Mr. Lentin Joseph.](https://www.linkedin.com/in/lentinjoseph/).

Here, I shall go over the approach taken and briefly discuss how one can implement the same. Unfortunately, this work is not open-source, but I am working on a similar implementation for the same and it will roll out soon!
Here are the steps:

- First, we start of by setting up cameras around the gantry, such that it covers all the parts of the car.(later used for 3D reconstruction of the car in pointcloud format.)

- We then collect images from these cameras and these images correspond to the parts of the car that is recorded in the camera frame, to be painted.

-We also collect the point cloud from each camera, and concatenate them together, to acquire entire car in a 3D pointcloud format.

- This is used for creating an octomap to perform collision avoidance while performing painting action.

- Using the segmented images and it's corresponding pointcloud, we generate waypoints for computing cartesian plan.


## Future Work

Happy Exploring!
