cmake_minimum_required(VERSION 3.24)
project(Printf C)

set(CMAKE_C_STANDARD 11)

add_executable(Printf main.c _printf.c get_flags.c get_width.c get_precision.c get_size.c handle_print.c get_width.c functions.c functions1.c functions2.c utils.c write_handlers.c)
