cmake_minimum_required(VERSION 3.5)

project(compile_test)

# set the C++ standard
set(CMAKE_CXX_STANDARD 11)

set(CMAKE_WINDOWS_EXPORT_ALL_SYMBOLS ON)

add_executable(${PROJECT_NAME}.exe main.cpp)
