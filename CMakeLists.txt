cmake_minimum_required(VERSION 3.29)
project(PathFinder)

set(CMAKE_CXX_STANDARD 20)

add_executable(PathFinder main.cpp src/sipp/sipp.h
        src/cbs/cbs.h)
