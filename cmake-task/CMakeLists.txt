cmake_minimum_required(VERSION 3.16)

project(calculator LANGUAGES C)

add_executable(calculator src/main.c src/calculator.c)

target_include_directories(calculator PUBLIC include)
