cmake_minimum_required(VERSION 3.21)
project(tpProgSysShell C)

set(CMAKE_C_STANDARD 99)

add_executable(tpProgSysShell main.c displayFunctions.c headers.h)
