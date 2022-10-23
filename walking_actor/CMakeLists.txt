cmake_minimum_required(VERSION 3.5)

project(walking_actor)

find_package(catkin REQUIRED)

catkin_package()

install(
  DIRECTORY
    launch/
  DESTINATION
    ${CATKIN_PACKAGE_SHARE_DESTINATION}/launch
)

install(
  DIRECTORY
    rviz/
  DESTINATION
    ${CATKIN_PACKAGE_SHARE_DESTINATION}/rviz
)
