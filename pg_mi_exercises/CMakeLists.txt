cmake_minimum_required(VERSION 3.6)
project(pg_mi_exercises)

# Paper 01
add_subdirectory(paper_01/task_01)
add_subdirectory(paper_01/task_02)
add_subdirectory(paper_01/task_03)
add_subdirectory(paper_01/task_04)
add_subdirectory(paper_01/task_05)
add_subdirectory(paper_01/task_06)
add_subdirectory(paper_01/task_07)

# Paper 02
add_subdirectory(paper_02/task_01)
add_subdirectory(paper_02/task_02)
add_subdirectory(paper_02/task_03)
add_subdirectory(paper_02/task_04)
add_subdirectory(paper_02/task_05)
add_subdirectory(paper_02/task_06)
add_subdirectory(paper_02/task_07)
add_subdirectory(paper_02/task_08)

# Paper 03
add_subdirectory(paper_03/task_01)
add_subdirectory(paper_03/task_02)
add_subdirectory(paper_03/task_03)
add_subdirectory(paper_03/task_04)
add_subdirectory(paper_03/task_05)
add_subdirectory(paper_03/task_06/v1)
add_subdirectory(paper_03/task_06/v2)

# Paper 04
add_subdirectory(paper_04/task_01)
add_subdirectory(paper_04/task_02)
add_subdirectory(paper_04/task_04)

# Paper 05
add_subdirectory(paper_05/task_01)
add_subdirectory(paper_05/task_02)
add_subdirectory(paper_05/task_03)
add_subdirectory(paper_05/task_04)

# Strings
add_subdirectory(strings/strlen)
add_subdirectory(strings/strnlen)

add_subdirectory(strings/strcmp)
add_subdirectory(strings/strncmp)

add_subdirectory(strings/strcat)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -Werror")