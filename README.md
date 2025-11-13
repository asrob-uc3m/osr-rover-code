# JPL Open Source Rover Code

Repository forked from: [open source rover ros (osr)](https://github.com/nasa-jpl/osr-rover-code).

The rover runs on ROS2.

Testing with Ubuntu 22.04 and ROS2 Humble (In progress).
## Installation
```bash
cd ROS
colcon build
source install/setup.bash
ros2 launch osr_bringup osr_launch.py
```