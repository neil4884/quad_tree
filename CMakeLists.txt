cmake_minimum_required(VERSION 3.23)
project(quad_tree)

set(CMAKE_CXX_STANDARD 11)

add_executable(main main.cpp)
add_executable(test test.cpp)

add_executable(bench_fill_tree bench_fill_tree.cpp)