cmake_minimum_required(VERSION 3.11)
project(veno-script CXX)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY .build)

set(CMAKE_CXX_STANDARD 23)

add_executable(veno-script main.cpp)
