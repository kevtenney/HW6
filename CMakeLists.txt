cmake_minimum_required(VERSION 3.8)
project(HW6)

set(CMAKE_CXX_STANDARD 11)

#set(SOURCE_FILES main.cpp)
set(SOURCE_FILES SuperArray.cpp SuperArray.h testArray.cpp)
add_executable(HW6 ${SOURCE_FILES})