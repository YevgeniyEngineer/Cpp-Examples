cmake_minimum_required(VERSION 3.18)

project(cpp_20_examples)

set(CXX_STANDARD 20)
set(CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++20")

add_executable(optional optional.cpp)
add_executable(any any.cpp)
add_executable(variant variant.cpp)
add_executable(concept concept.cpp)
add_executable(structure_binding structure_binding.cpp)
add_executable(span span.cpp)
add_executable(jthread jthread.cpp)
add_executable(three_way_comparison three_way_comparison.cpp)
add_executable(range range.cpp)
add_executable(coroutine coroutine.cpp)
add_executable(integer_comparison integer_comparison.cpp)