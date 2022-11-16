cmake_minimum_required(VERSION 3.21)
project(n1)

set(CMAKE_CXX_STANDARD 14)
find_package(Threads REQUIRED)
add_executable(n1 main.cpp)
target_link_libraries(n1 Threads::Threads )