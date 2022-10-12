cmake_minimum_required(VERSION 3.10.2)
project(cam_det)

find_package(OpenCV)
include_directories(${OpenCV_INCLUDE_DIRS})
add_executable(cam_executable cam.cpp)
target_link_libraries(cam_executable ${OpenCV_LIBRARIES})
