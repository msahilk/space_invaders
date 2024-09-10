cmake_minimum_required(VERSION 3.28)
project(space_invaders)

set(CMAKE_CXX_STANDARD 17)

add_executable(space_invaders main.cpp)


target_link_libraries(space_invaders GLEW GL glfw )


