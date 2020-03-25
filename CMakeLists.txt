cmake_minimum_required(VERSION 2.6)
project(say_hello)
add_executable(say_hello main.c)
install(TARGETS say_hello DESTINATION bin)
