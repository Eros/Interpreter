cmake_minimum_required(VERSION 3.16)
project(TwitchInterpreter C)

set(CMAKE_C_STANDARD 11)

add_executable(TwitchInterpreter main.c hashmap.h hashmap.c token.h object.h ast.h lexer.h lexer.c parser.h parser.c)