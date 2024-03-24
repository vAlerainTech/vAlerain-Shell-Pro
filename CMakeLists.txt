cmake_minimum_required(VERSION 3.27)
project(vAlerainShell)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(vAlerainShell
        all.h
        main.cpp
        vAlerainShell_private.h)
