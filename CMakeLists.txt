cmake_minimum_required(VERSION 3.10)

project(ProjectMemPool)
set (CMAKE_CXX_STANDARD 11)
file(GLOB SOURCES ${CMAKE_CURRENT_SOURCE_DIR}/*.cpp)
include_directories(C-11)
add_executable(mempool ${SOURCES})

