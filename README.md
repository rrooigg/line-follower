### Robotics Simulations
## 01 Line Follower Robot

# Project Overview
Line follower robot is an autonomous mobile robotic system designed to move along a predefined path by detecting and following the red line on the floor.

# Robot Structure
1. Joints- connects the wheels to the robot base and allows the wheels to turn.
2. Wheels- allows the robot to move around.
3. Sensors- detect the red line and surface based on differences in color/contrast.
4. Base- supports the main body and holds the components together.

# How it works/Algorithm
The robot uses its sensors to detect the red line on the floor. Then based on the sensor readings the velocities of the wheel joints are adjusted to steer the robot accordingly. 
-**Right Sensor**: If the right sensor recorded a reading of 0.5 or below that means it's on the red line and the velocity of the left wheel joint is increased and the robot moves to right so that both sensors can now see/read from the red line. 
**Left Sensor**: When the left sensor reads a reading of 0.5 or below(meaning it's on the red line) then the velocity of the right wheel joint is increased and the line follower moves towards the left and both sensors can now see/read from thee red line.

# Software and Tools Used
1. CoppeliaSim Edu- for simulation
2. Python Programming language- used to implement the control algorithm and process sensor readings.

# Results
The video below demonstrates the robot successfully following the red path.
https://github.com/user-attachments/assets/816f3a00-9037-491f-bb0e-fa189d63781d

