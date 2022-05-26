cmake_minimum_required(VERSION 3.22)
project(Pacman CXX)

set(CMAKE_CXX_STANDARD 11)
find_package(GLUT 3.7)
include_directories( ${OPENGL_INCLUDE_DIRS}  ${GLUT_INCLUDE_DIRS} )

add_executable(Pacman main.cpp)
