add_executable(iarrc_motor_relay_node iarrc_motor_relay_node.cpp)
target_link_libraries(iarrc_motor_relay_node ${catkin_LIBRARIES})
add_dependencies(iarrc_motor_relay_node ${iarrc_msgs_EXPORTED_TARGETS})
