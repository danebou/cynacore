cmake_minimum_required (VERSION 2.6)
project (cynacore)
set(CMAKE_CXX_STANDARD 11)  # enable C++11 standard
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++1y -Wall")

include_directories(include)
file(GLOB SOURCES "src/*.cpp")

add_executable(cynacore ${SOURCES})