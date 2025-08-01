# manipulating-turtlesim-package-in-ROS2

A window opens with a turtle in it.
ros2 run turtlesim turtlesim_node

Move the turtle with arrows.
ros2 run turtlesim turtle_teleop_key

View list of topics.
ros2 topic list

Send a message to the turtle.
ros2 topic pub /turtle1/cmd_vel geometry_msgs/msg/Twist "{linear: {x: 2.0}, angular: {z: 1.0}}"
