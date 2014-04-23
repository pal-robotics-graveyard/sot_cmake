cmake_minimum_required(VERSION 2.8.3)
project(sot_cmake)

find_package(catkin REQUIRED)

catkin_package(
  CFG_EXTRAS sot_cmake-extras.cmake
)

install(DIRECTORY cmake
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
