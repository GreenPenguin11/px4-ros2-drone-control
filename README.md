# px4-ros2-drone-control
ROS2 nodes for PX4 drone offboard hover control with arm/disarm and (slightly dubious) obstacle avoidance features.

# Nodes
- **hover.py**

  _This node was developed entirely by me during MIT BWSI. It implements offboard hovering for a PX4 drone using ROS2 and allows user input for target waypoints and incorporates arm/disarm capabilities._
  
  Note: The final version (unfortunately lost) also supported parsing waypoints from a YAML file to allow for path following capabilities.

  
- **obstacle_avoidance.py** and **obstacle_avoidance_input.py**

  _These nodes were developed collaboratively with my teammates. The first implements obstacle avoidance logic using real-time distance sensor data, while the second is console-driven._

  Note: These versions are also not the final ones used in the final flight.

