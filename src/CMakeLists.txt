
cmake_minimum_required(VERSION 3.8)
set(CMAKE_C_STANDARD 99)

include_directories(../libxxx)

set(SOURCE_FILES main.c)

add_executable(fassle ${SOURCE_FILES})
target_include_directories(fassle PUBLIC ../libxxx)
target_link_libraries(fassle LINK_PUBLIC libxxx)
