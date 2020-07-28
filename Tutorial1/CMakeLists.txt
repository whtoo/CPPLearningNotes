# CMake 最低版本要求
cmake_minimum_required(VERSION 3.1)
# 项目信息
project(CPPTutorial1)
set(CMAKE_CXX_STANDARD 11)
aux_source_directory(. DIR_SRCS)

add_executable(Tutorial1 main.cpp)