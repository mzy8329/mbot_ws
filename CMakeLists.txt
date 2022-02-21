cmake_minimum_required(VERSION 3.0.2)
project(mbot_gazebo)


find_package(catkin REQUIRED COMPONENTS
  roscpp
)

find_package(GAZEBO REQUIRED)



include_directories(
  include
  ${catkin_INCLUDE_DIRS}
  ${GAZEBO_INCLUDE_DIRS} 
  # ${SDFormat_INCLUDE_DIRS}
)


catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES mbot_gazebo
#  CATKIN_DEPENDS roscpp
#  DEPENDS system_lib

  # DEPENDS
  # gazebo_ros
  # CATKIN_DEPENDS
  # INCLUDE_DIRECTORIES
  # LIBRARIES
)
