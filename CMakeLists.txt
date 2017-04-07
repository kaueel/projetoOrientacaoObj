cmake_minimum_required(VERSION 3.6)
project(FT_Bakery)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        a02ex00.cpp
        a02ex00.hpp
        a02ex01_a.cpp
        a02ex01_a.hpp
        a02ex03.cpp
        a02ex03.hpp
        a02ex03_a.cpp
        a02ex03_a.hpp
        a02ex03_b.cpp
        a02ex03_b.hpp
        a02ex03_c.cpp
        a02ex03_c.hpp
        a02ex03_d.cpp
        a02ex03_d.hpp
        a02ex03_e.cpp
        a02ex03_e.hpp
        lista.txt)

add_executable(FT_Bakery ${SOURCE_FILES})