cmake_minimum_required(VERSION 3.20)
project(CppSelfCheck)

set(CMAKE_CXX_STANDARD 17)

# Main executable.
set(EXE_MAIN ${PROJECT_NAME}_exe)
add_executable(${EXE_MAIN} main.cpp)
