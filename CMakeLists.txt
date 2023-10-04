cmake_minimum_required(VERSION 3.26)
project(my_project C)
set(CMAKE_C_STANDARD 11)
add_executable(my_project_executable main.c helper.c)