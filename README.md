# The frozen tag problem

The frozen tag problem (FTP) is a challenging computational problem involving the activation of a swarm of K frozen robots. Typically, robots remain inactive to conserve energy until an individual robot detects an external event (such as a fire or intrusion). At this point, all robots must be activated and set up to perform specific tasks. However, in order for robots to communicate, they must be physically close to each other, so all robots must be woken up in advance.

To activate a robot, the awakened robot must move to the position of the stationary robot. Once activated, the robot can help wake others up. The goal of FTP is to wake up all robots in the shortest possible time.

# Project objective

The goal of this project is to design and implement an algorithm for solving the FTP problem. Robots have the following behavioral characteristics:
    - Each robot has a constant uniform speed of movement.
    - To wake a robot, the awakened robot must be placed directly above it.
    - Each robot knows the starting position of all robots.
