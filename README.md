# UTFPR Francisco Beltrão Workshop/Presentations
This repository has been created as a tutorial of how to run ROS 2 with a real Turtlebot 3. This is based on the official ROS 2 [tutorial](https://ros2-industrial-workshop.readthedocs.io/en/latest/_source/navigation/ROS2-Turtlebot.html).

## Our Robot
We play with the Turtlebot3 toy robot, which contains a LIDAR sensor and a camera.

## Xiaomi Cloud

For you to communicate with the original Vacuum system, you need to pass by Xiaomi Cloud. For this, you need the token of the Vacuum. 

To get the token, follow [this](https://github.com/PiotrMachowski/Xiaomi-cloud-tokens-extractor.git) tutorial.

Then, set it globally:
```bash
export VACUUM_X_TOKEN=<token>
echo "export VACUUM_X_TOKEN=<token>" >> ~/.bashrc
```

