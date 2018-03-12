# Programming

#### General Information & Overview

* Custom Node Framework designed entirely by Team 5940 students
* Over 500 commits to master across all our various Git repositories
* Uses Gradle for build and deploy to RoboRio
* Travis CI for automatic doc building
* Students have freedom to use many different develop environments

#### Node Framework

* Uses Nodes to do actions
* Is in the form of a directed asyclic graph
* Nodes are updated every update cycle and either update their stored value or perform an action based on other Node's values

#### Autonomous Path Planning

* An ordered list actions the robot will do during auto
* Actions can be moving forward, turning, outtaking a cube, or raising the elevator
* Uses PID control to move a specified distance
* Selects the proper list of actions based on the starting position of the robot, and the randomized switch and scale positions

#### Elevator Control

* Uses PID to move the elevator to a set position
* Sets the elevator height based on how far the joystick is moved. 
