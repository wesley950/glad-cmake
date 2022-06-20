cmake_minimum_required(VERSION 3.16)
project(glad_cmake)
add_library(glad_cmake glad/glad.c glad/glad.h glad/khrplatform.h)
target_include_directories(${PROJECT_SOURCE_DIR})