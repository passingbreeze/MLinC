cmake_minimum_required(VERSION 3.11)
project(MLinC)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_C_STANDARD 11)
link_libraries(-ltensorflow)

add_executable(MLinC main.cpp)