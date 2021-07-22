cmake_minimum_required(VERSION 3.19)
project(minesweeper_rawvf C)

set(CMAKE_C_STANDARD 11)

add_executable(minesweeper_rawvf
        src/parser_raw.c)
