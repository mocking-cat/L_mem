cmake_minimum_required(VERSION 3.4 FATAL_ERROR)

project(mem CXX)

add_library(mem INTERFACE)

target_include_directories(mem INTERFACE include)
