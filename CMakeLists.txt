cmake_minimum_required(VERSION 3.12)
project(Dijkstra_Algorithm_Implementation)

include_directories("include")

file(GLOB SOURCES "src/*.cpp")

add_executable(Dijkstra_Algorithm_Implementation ${SOURCES})