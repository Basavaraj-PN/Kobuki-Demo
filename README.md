# Kobuki-Demo

# Hardware Bringup 
`roslaunch rplidar_ros rplidar.launch` 

`roslaunch kobuki_node robot_with_tf.launch`

#  mapping
`roslaunch kobuki_slam kobuki_slam.launch`
`roslaunch kobuki_keyop keyop.launch`
`roslaunch kobuki_slam save_map.launch`  

#  Navigation 
`roslaunch kobuki_navigation kobuki_navigation.launch` 
