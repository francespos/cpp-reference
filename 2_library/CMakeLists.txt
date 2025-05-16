cmake_minimum_required(VERSION 3.10)
project(Lib)
add_subdirectory(src)

if(DEFINED LIB_TEST)
    add_subdirectory(test)
endif()