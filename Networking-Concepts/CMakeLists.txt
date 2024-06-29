# CMakeList.txt : CMake project for Networking-Concepts, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project(Networking_Concept VERSION 1.0.0 LANGUAGES C CXX)

set(CMAKE_C_STANDARD          17)
set(CMAKE_C_STANDARD_REQUIRED ON)
set(CMAKE_C_EXTENSIONS        OFF)

add_subdirectory(ip_math)
