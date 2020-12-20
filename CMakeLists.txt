project(st C)
set(CMAKE_C_STANDARD 99)

cmake_minimum_required(VERSION 3.19)

add_executable(st arg.h config.h st.h win.h st.c x.c)