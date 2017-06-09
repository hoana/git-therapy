
cmake_minimum_required(VERSION 3.5)
set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES
        sayhi.c
        sayhi.h)

add_library(libxxx ${SOURCE_FILES})

target_include_directories (libxxx PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
