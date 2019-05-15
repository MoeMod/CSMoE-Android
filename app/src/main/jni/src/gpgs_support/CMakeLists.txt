cmake_minimum_required(VERSION 2.8.0)
project(gpgs_support)

set(CMAKE_CXX_STANDARD 11)

add_library(gpgs_support SHARED gpgs_support.cpp)
target_link_libraries(gpgs_support log)
