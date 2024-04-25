# Multi-Turtlebot3-Nav2
Multi Robot (TurtleBot 3) Navigation and Gazebo.

'main' -> ROS2 Humble

## Run without nav2 stack
```
## Run with Gazebo
ros2 launch turtlebot3_multi_robot gazebo_multi_world.launch.py enable_drive:=True

## Run with nav2 stack
ros2 launch turtlebot3_multi_robot gazebo_multi_nav2_world.launch.py  use_sim_time:=True
```

```
Names and poses for the robots in nav2 example
 robots = [
 {'name': 'tb1', 'x_pose': '-1.5', 'y_pose': '-0.5', 'z_pose': 0.01},
 {'name': 'tb2', 'x_pose': '-1.5', 'y_pose': '0.5', 'z_pose': 0.01},
 # …
 ]
```
