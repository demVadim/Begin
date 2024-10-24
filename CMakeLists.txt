# general info
cmake_minimum_required(VERSION 3.31.0-rc1 FATAL_ERROR)

set(PROJECT_NAME BattleArena VERSION 1.0.0)

project(${PROJECT_NAME})

add_subdirectory(code)
# common option



# cpp option 
set(CMAKE_CXX_STANDART 17)



message("Project ---- ${PROJECT_NAME} ---- cpp version ${CMAKE_CXX_STANDART}")
