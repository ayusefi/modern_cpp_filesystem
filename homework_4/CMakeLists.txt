cmake_minimum_required(VERSION 3.1)
project(modern_cpp_filesystem)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_library(homework_4 homework_4.cpp)
add_executable(main main.cpp)
target_link_libraries(main homework_4)
