# Specify the minimum version for CMake

cmake_minimum_required(VERSION 2.8)

# Project's name

project(example)

add_executable(example example.c memorypool.c)
add_executable(test test.cpp memorypool.h memorypool.c bostree/bostree.h bostree/bostree.c)
