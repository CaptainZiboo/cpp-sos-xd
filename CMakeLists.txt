cmake_minimum_required(VERSION 3.10)

project(server)

# Ajoutez cette ligne pour inclure les packages vcpkg
include_directories("${CMAKE_PREFIX_PATH}/include/")

add_executable(server server.cpp)
