cmake_minimum_required (VERSION 3.20.1)

project("glad" C)

add_library(${CMAKE_PROJECT_NAME} STATIC "src/glad.c")

target_include_directories(${CMAKE_PROJECT_NAME} PUBLIC "include")