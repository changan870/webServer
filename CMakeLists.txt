cmake_minimum_required(VERSION 3.17)
project(web)

set(CMAKE_CXX_STANDARD 14)

add_executable(web main.cpp locker.cpp http_conn.cpp threadpool.cpp)