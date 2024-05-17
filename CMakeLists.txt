cmake_minimum_required(VERSION 3.28)
project(Lesson03_Graphs)

set(CMAKE_CXX_STANDARD 20)

add_executable(Lesson03_Graphs main.cpp
        vertex.h
        edge.h
        graph.h)
