cmake_minimum_required(VERSION 3.6)
project(Inner CXX)

add_library(inner inner.cpp)
target_include_directories(inner PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}")