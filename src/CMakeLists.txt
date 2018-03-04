
# CMake Minimum Version Requirement
cmake_minimum_required(VERSION 3.10.2)

# Project Name
project(clargs)

# Compiler Arguments 
add_definitions(-std=c++17)

# Build
add_executable(clargs-demo clargs-demo.cpp)

