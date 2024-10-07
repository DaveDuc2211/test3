cmake_minimum_required(VERSION 3.28)
project(test3)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(test3
        test.cpp
        test.h
        tests.c)
