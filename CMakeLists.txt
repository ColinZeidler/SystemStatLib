cmake_minimum_required(VERSION 3.5)
project(SystemStatLib)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(SystemStatLib ${SOURCE_FILES})