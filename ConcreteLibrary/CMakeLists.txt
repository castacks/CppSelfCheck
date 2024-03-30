cmake_minimum_required(VERSION 3.20)
project(ConcreteLibrary)

set(CMAKE_CXX_STANDARD 17)

set(LIB_NAME concrete)

add_library(${LIB_NAME} SHARED src/ConcreteLibrary.cpp)
