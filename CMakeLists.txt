cmake_minimum_required(VERSION 3.28)
project(test C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(test
        rfc1321/global.h
        rfc1321/md5.h
        rfc1321/md5c.c
        mddriver.c
        md5-engine.c)
