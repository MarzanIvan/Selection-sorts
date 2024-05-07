cmake_minimum_required(VERSION 3.27)


project(SelectionSort)

set(CMAKE_CXX_STANDARD 11)

add_executable(SelectionSort selectsort.cxx
        selectsort.hxx)