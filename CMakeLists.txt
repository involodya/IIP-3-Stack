cmake_minimum_required(VERSION 3.20)
project(IIP_3_Stack)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(IIP_3_Stack
        defines.h
        dump.cpp
        dump.h
        main.cpp
        stack.cpp
        stack.h)
