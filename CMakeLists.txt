cmake_minimum_required(VERSION 3.3)
project(lab5)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp vector2d.cpp)
add_executable(lab5 ${SOURCE_FILES})