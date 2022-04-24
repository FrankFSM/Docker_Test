cmake_minimum_required(VERSION 3.20)
project(Docker_Test)

set(CMAKE_CXX_STANDARD 14)

add_executable(Docker_Test main.cpp host_namespace.c ipc_namespace.c pid_namespace.c)
