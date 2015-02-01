cmake_minimum_required(VERSION 2.8.3)
project(neato_node)

set(CMAKE_BUILD_TYPE Debug)

find_package(catkin REQUIRED)
catkin_package(DEPENDS)

install(DIRECTORY launch
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

install(DIRECTORY nodes
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
