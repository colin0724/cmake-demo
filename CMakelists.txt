cmake_minimum_required(VERSION 2.8.4) 

project(demo)

set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${PROJECT_BINARY_DIR}/lib)
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${PROJECT_BINARY_DIR}/bin)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${PROJECT_BINARY_DIR}/bin)

# add_definitions(-std=c++11)

set(SERVER_SRC main.cpp)
add_executable(demo ${SERVER_SRC})