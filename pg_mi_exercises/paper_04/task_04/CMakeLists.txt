cmake_minimum_required(VERSION 3.6)
project(paper_04_task_04 C)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DMOVIES=OFF -Wall -Werror -Wno-deprecated -Wno-error=deprecated")

find_package(PkgConfig REQUIRED)
pkg_check_modules(GTK3 REQUIRED gtk+-3.0)

include_directories(${GTK3_INCLUDE_DIRS})
link_directories(${GTK3_LIBRARY_DIRS})

add_definitions(${GTK3_CFLAGS_OTHER})

set(SOURCE_FILES main.c main.c)
add_executable(paper_04_task_04 ${SOURCE_FILES})
target_link_libraries(paper_04_task_04 ${GTK3_LIBRARIES})