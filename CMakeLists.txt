cmake_minimum_required(VERSION 3.6)

PROJECT (tinygltf)

SET(CMAKE_CXX_STANDARD 11)

add_library(tinygltf STATIC tiny.cpp)

target_include_directories(tinygltf PUBLIC include)
