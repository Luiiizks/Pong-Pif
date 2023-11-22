cmake_minimum_required(VERSION 3.26)
project(Pong_C C)

set(CMAKE_C_STANDARD 11)

include_directories(include)

add_executable(Pong_C
        include/keyboard.h
        include/screen.h
        include/timer.h
        src/keyboard.c
        src/main.c
        src/screen.c
        src/timer.c)
