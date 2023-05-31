cmake_minimum_required(VERSION 3.0 FATAL_ERROR)
project(hello-world)
add_executable(hello-world main.c)
install(TARGETS hello-world)