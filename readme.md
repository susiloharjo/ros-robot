# ros-robot

## this is my setting for my ros project
- Follow my project at  y blog https://kakeko.wordpress.com

ros distro noetic

src ros_rplidar https://github.com/robopeak/rplidar_ros
source devel/setup.bash
roscore
roslaunch rplidar_ros rplidar.launch
roslaunch rplidar_ros view_rplidar.launch
roslaunch hector_slam_launch tutorial.launch


#remote teleops
- rosrun rosserial_python serial_node.py _port:=/dev/ttyUSB0
- rosrun rqt_robot_steering rqt_robot_steering
- rosrun teleop_twist_keyboard teleop_twist_keyboard.py


