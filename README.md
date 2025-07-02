# Walking Robot Examples
Copyright 2017-2019 The MathWorks, Inc.

## Introduction
This repository contains example files for the following [MATLAB and Simulink Robotics Arena](https://www.mathworks.com/academia/student-competitions/roboticsarena.html) videos on walking robots.

* [Basics of walking robots](https://www.mathworks.com/videos/model-based-control-of-humanoid-walking-1574399243682.html)
* [Modeling and simulation](https://www.mathworks.com/videos/modeling-and-simulation-of-walking-robots-1576560207573.html)
* [Trajectory optimization](https://www.mathworks.com/videos/matlab-and-simulink-robotics-arena-walking-robots-part-3-trajectory-optimization-1506440520726.html)
* [Walking pattern generation](https://www.mathworks.com/videos/matlab-and-simulink-robotics-arena-walking-robots-pattern-generation-1546434170253.html)
* [Deep reinforcement learning](https://www.mathworks.com/videos/matlab-and-simulink-robotics-arena-deep-reinforcement-learning-for-walking-robots--1551449152203.html)

You can also learn more about this example from our blog posts on 
[modeling and simulation](https://blogs.mathworks.com/racing-lounge/2017/10/11/walking-robot-modeling-and-simulation) 
and [control](https://blogs.mathworks.com/racing-lounge/2019/04/24/walking-robot-control/).

For any questions, email us at roboticsarena@mathworks.com.

---

## Setup
Run `startupWalkingRobot.m` to get the MATLAB path ready.

Below are the main folders containing various walking robot examples:

1.  `LIPM` -- Shows how to generate a walking pattern using the 
linear inverted pendulum model (LIPM), which is one of the foundational 
models for humanoid walking control.

2. `ModelingSimulation` -- Shows how to build the simulation of the walking 
robot, including contact forces, various actuator models, and importing from CAD.

3. `Optimization` -- Shows how to use genetic algorithms to optimize joint angle
trajectories for stability and speed.

4. `ControlDesign` -- Shows how to create closed-loop walking controllers 
using common techniques like Zero Moment Point (ZMP) manipulation and 
Model Predictive Control (MPC) for pattern generation.

5. `ReinforcementLearning` -- Shows how to set up and train a Deep Deterministic 
Policy Gradient (DDPG) reinforcement learning agent for learning how to walk.

Each of these folders has its own separate README with more information.

---

## Multiphysics Library
For convenience, a local copy of the Simscape Multibody Multiphysics Library 
has been included with this submission. If you would like to install the 
latest version of these libraries, you can find them from the Add-On Explorer, 
or on the File Exchange at https://www.mathworks.com/matlabcentral/fileexchange/37636-simscape-multibody-multiphysics-library
