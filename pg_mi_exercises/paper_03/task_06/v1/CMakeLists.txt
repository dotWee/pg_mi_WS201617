cmake_minimum_required(VERSION 3.6)
project(paper_03_task_06v1)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -Werror")

add_library(paper_03_task_06v1_Map libs/map.c)
set(SOURCE_FILES main.c main.c)
add_executable(paper_03_task_06v1 ${SOURCE_FILES})
target_link_libraries(paper_03_task_06v1 paper_03_task_06v1_Map)