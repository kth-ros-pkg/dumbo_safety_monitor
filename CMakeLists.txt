cmake_minimum_required(VERSION 2.8.3)
project(dumbo_safety_monitor)

find_package(catkin REQUIRED)
catkin_package()
catkin_python_setup()

install(PROGRAMS scripts/dumbo_safety_monitor
  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)