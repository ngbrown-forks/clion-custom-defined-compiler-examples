cmake_minimum_required(VERSION 3.21)

project(CMake-NetBurner-m68k-GNU C CXX)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
set(CMAKE_C_STANDARD 99)

add_link_options()
add_executable(CMake-NetBurner-m68k-GNU main.cpp cmain.c)

