cmake_minimum_required(VERSION 3.7)

if (POLICY CMP0025)
  cmake_policy(SET CMP0025 NEW)
endif ()

project(NES)

set (CMAKE_CXX_STANDARD 20)

add_executable(main main.cpp)

