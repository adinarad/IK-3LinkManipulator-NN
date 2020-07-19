# Inverse Kinematics Of 3 Link Planar Robot Manipulator Using Data Driven Approach
***This project was completed under the guidance of [Prof. Vijay Bhaskar Semwal](https://sites.google.com/site/wwwvbsemwalcom/).***

This project focuses on solving the inverse kinematics problem, for a 3L Planar Robot Manipulator, which is used to transform a position of the end-effector in the Cartesian space to a set of joint angles.

## What it does?
After training the model, the coordinates and orientation of the points on the desired trajectory in the Cartesian space can be applied as inputs to the neural network, which will produce the joint parameters that place the end effector on the required trajectory.

## Why is it useful?
Although there are several different procedures available, which are based on the known geometry of the manipulator, to solve the inverse kinematics problem. However, these solutions become more difficult, or impractical, when the manipulator geometry cannot be determined exactly. Therefore, this poses a question as to whether any alternative solution to determine the inverse kinematics transformation exists if the geometry of the manipulator is unknown. A possible approach is to use neural networks to learn the inverse kinematics transformation.
