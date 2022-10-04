cmake_minimum_required(VERSION 3.5)

project(4_stibe LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(4_stibe main.cpp)

install(TARGETS 4_stibe
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR})
