cmake_minimum_required(VERSION 3.6)
project(task_04_potenzen)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -Werror")

set(SOURCE_FILES getpower.c getpower.c)
add_executable(task_04_potenzen ${SOURCE_FILES})