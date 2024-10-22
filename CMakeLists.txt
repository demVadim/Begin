# general info
cmake_minimum_required(VERSION 3.31.0-rc1 FATAL_ERROR)

set(PROJECT_NAME BattleArena VERSION 1.0.0)
project(${PROJECT_NAME})

# cpp option
set(CMAKE_CXX_STANDART 17)

add_executable(${PROJECT_NAME} main.cpp)

message("Project ---- ${PROJECT_NAME} ---- cpp version ${CMAKE_CXX_STANDART}")
