1st TASK - MAPPING

To launch the mapping process navigate to ros2_ws folder.

$ cd ~/ros2_ws
Launch the mapping process:


$ ros2 launch my_robot_controller start_mapping.launch.py

Save the map:

ros2 run nav2_map_server map_saver_cli -f ~/ros2_ws/my_robot_controller/maps/my_map
