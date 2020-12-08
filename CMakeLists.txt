cmake_minimum_required(VERSION 3.18)
project(mimp LANGUAGES CXX)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

find_package(Threads)

add_subdirectory(src)
add_subdirectory(test)
