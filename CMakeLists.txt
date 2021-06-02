cmake_minimum_required(VERSION 3.19)
project(epoll_c C)

set(CMAKE_C_STANDARD 99)

add_executable(client.c client.c)
add_executable(server.c server.c)