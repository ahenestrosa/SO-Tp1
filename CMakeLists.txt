cmake_minimum_required(VERSION 3.14)
project(SO-Tp1 C)

set(CMAKE_C_STANDARD 99)

set(GCC_COVERAGE_COMPILE_FLAGS "-lrt -pthread")

add_executable(SO-Tp1 source source/view.c utils include)

TARGET_LINK_LIBRARIES(SO-Tp1 -lrt -pthread)