cmake_minimum_required(VERSION 3.3..3.18)

project(helloworld VERSION 0.1.0 LANGUAGES C)

add_executable(helloworld src/helloworld.c)

include(CPack)
