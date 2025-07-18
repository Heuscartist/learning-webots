# 4-Wheeled Robot in Webots

This project implements a simple 4-wheeled differential drive robot in [Webots](https://cyberbotics.com/), using Python as the controller language. The robot uses two distance sensors to detect obstacles and performs basic avoidance behavior.

## Robot Overview

### Diagram
![Robot View](./4_wheeled_robot.jpg)

### Schematic Representation
![Representation](./4_wheeled_robot_representation.jpg)

### Demo Animation
![Demo](./4_wheeled_robot.gif)

## Behavior Description

- The robot uses two distance sensors (`ds_right` and `ds_left`) to monitor obstacles.
- When an obstacle is detected by either sensor (value < 950), the robot initiates a turn by reversing one set of wheels for a few steps.
- Otherwise, it moves forward continuously.

## Resource Used
The official webots [tutorial](https://cyberbotics.com/doc/guide/tutorial-6-4-wheels-robot?tab-language=python) was used as a guide to implement this 4-wheeled robot. For more details on how to create the robot itself and set up the environement refer to the tutorial.
