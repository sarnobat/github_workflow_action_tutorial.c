cmake_minimum_required(VERSION 3.15)

project(hello)

add_executable(hello hello.c)

set_target_properties(hello PROPERTIES OUTPUT_NAME "hello2.${CMAKE_SYSTEM_NAME}")
