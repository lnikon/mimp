cmake_minimum_required(VERSION 3.18)
project(mimp LANGUAGES CXX)

add_executable(mimp_main main.cpp)
target_compile_features(mimp_main PUBLIC cxx_std_17)
