cmake_minimum_required(VERSION 2.6.0)

set(CMAKE_EXPORT_COMPILE_COMMANDS 1)
project(dwm C)

add_definitions(-w)

set(SOURCE_FILES dwm.c drw.c shiftview.c transient.c util.c vanitygaps.c)

add_executable(dwm ${SOURCE_FILES})
