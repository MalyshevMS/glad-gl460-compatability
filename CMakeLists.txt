cmake_minimum_required(VERSION 3.25 FATAL_ERROR)

project(Glad)

add_library(glad STATIC glad/include/glad/glad.h glad/src/glad.c)
target_include_directories(glad PUBLIC glad/include/)
