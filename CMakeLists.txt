cmake_minimum_required(VERSION 4.1)
project(Clion C)

set(CMAKE_C_STANDARD 11)

include_directories("01 Introduction to C World")

add_executable(Clion
        "01 Introduction to C World/hello.c"
        "02 Variables, Types, IO/01  test.c"
        "CPMA/03  IO/tprintf.c")
