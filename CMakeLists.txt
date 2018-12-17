cmake_minimum_required(VERSION 3.13 FATAL_ERROR)
project(argparse VERSION 1.02)

set(CMAKE_C_STANDARD 99)

add_library(argparse argparse.c argparse.h)
target_include_directories(argparse PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
