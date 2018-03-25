cmake_minimum_required(VERSION 3.7)
project(Epoll_Client)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES main.c)
add_executable(Epoll_Client ${SOURCE_FILES})