cmake_minimum_required(VERSION 2.6)
if (UNIX OR MINGW)
    add_definitions(-O3)
endif()
add_library(xxtea-c STATIC
    xxtea.c
)
