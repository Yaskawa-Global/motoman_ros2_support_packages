cmake_minimum_required(VERSION 3.12)

project(motoman_gp215_support NONE)

find_package(ament_cmake REQUIRED)
ament_package()

install(DIRECTORY meshes urdf
  DESTINATION share/${PROJECT_NAME})
