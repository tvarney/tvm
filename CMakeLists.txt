cmake_minimum_required (VERSION 3.2)
project (tvm)

include_directories(include)
file(GLOB SOURCES "source/*.cpp")

add_executable(tvm ${SOURCES})
