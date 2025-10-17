cmake_minimum_required(VERSION 3.12)

project(motoman_resources NONE)

find_package(ament_cmake REQUIRED)
ament_package()

install(DIRECTORY rviz urdf
  DESTINATION share/${PROJECT_NAME})
