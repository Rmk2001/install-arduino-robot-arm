# install-arduino-robot-arm
task 3&4


ROS packages that can be used to plan and execute motion trajectories for a robot arm in simulation and real-life.



These packages were tested under ROS kinetic and Ubuntu 16.04 and it works perfectly on ROS melodic and noetic

The robot arm uses Moveit plugin to apply kinematics by the KDL solver. These packages can be tested in the gazebo simulation tool and the real robot arm, where the ROS system and Arduino code share the ```/joint_states``` topic to control motors.

