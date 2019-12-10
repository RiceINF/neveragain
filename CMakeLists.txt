cmake_minimum_required(VERSION 3.8)
project(textadv)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Room.cpp Room.h wordwrap.h wordwrap.cpp State.cpp State.h strings.h cmake-build-debug/GameObject.cpp cmake-build-debug/GameObject.h)
add_executable(textadv ${SOURCE_FILES})