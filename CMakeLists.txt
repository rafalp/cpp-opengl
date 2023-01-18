cmake_minimum_required(VERSION 3.22)
project(gfx_engine)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR})

include_directories(include)

add_subdirectory(src)
