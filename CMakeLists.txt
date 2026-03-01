cmake_minimum_required(VERSION 4.1)
project(Trabalho C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(Trabalho
        abb.c
        abb.h
        grafo.c
        grafo.h
        main.c)
