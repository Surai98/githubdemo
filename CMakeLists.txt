cmake_minimum_required(VERSION 3.21)
project(githubdemo)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(githubdemo
        Bird.cpp
        Bird.h
        main.cpp)
