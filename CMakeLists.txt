# CMake minimum version
cmake_minimum_required(VERSION 3.10[3.31.4])

# Project name
project(cpp_hello_world)

# Set C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Executable target
add_executable(cpp_hello_world src/main.cpp)