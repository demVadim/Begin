set(CMAKE_CXX_STANDART 23)
set(CMAKE_CXX_STANDART_REQUIRED True)
set(CMAKE_CXX_STANDARD_LIBRARIES " ")

cmake_minimum_required(VERSION 3.31.0-rc1 FATAL_ERROR)

project(BattleArena)

add_subdirectory(code)
add_subdirectory(libraries)