cmake_minimum_required(VERSION 3.8)
project(cNetwork)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES server.c client.c)
add_executable(cNetwork ${SOURCE_FILES})