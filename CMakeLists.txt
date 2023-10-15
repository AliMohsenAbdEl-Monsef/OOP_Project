cmake_minimum_required(VERSION 3.23)
project(CS213_2023_2024_Assignment1_V1_0)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(
        bmplib.cpp
        bmplib.h
        main.cpp)