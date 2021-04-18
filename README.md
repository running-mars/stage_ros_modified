# stage_ros_modified

## introduction
Stage is a 2D simulation platform. Based on the repo shown below and the latest stage_ros, we modified stage_ros-add_pose_and_crash, in order to make it more stable.
> https://github.com/Acmece/rl-collision-avoidance/tree/master/stage_ros-add_pose_and_crash

> https://github.com/ros-simulation/stage_ros

## how to use
```bash
git clone git@github.com:running-mars/stage_ros_modified.git
mkdir -p catkin_ws/src
catkin_init_workspace
cd ..
mv stage_ros_modified/stage_ros-add_pose_and_crash_<slow/fast> catkin_ws/src/
catkin_make
```

## how to run 
```bash
cd catkin_ws
source devel/setup.bash
rosrun stage_ros_add_pose_and_crash stageros <world file>
```
