cmake_minimum_required(VERSION 3.2)

project(makx)

set(CMAKE_C_STANDARD 11)
set(CMAKE_C_FLAGS "-Wall")

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_FLAGS "-Wall")

add_executable(${PROJECT_NAME} main.cpp)
