cmake_minimum_required(VERSION 3.15)
project(socket)

set(CMAKE_CXX_FLAGS_DEBUG_INIT "-Wall -Wextra")

add_subdirectory(simple-echo)
add_subdirectory(echo)