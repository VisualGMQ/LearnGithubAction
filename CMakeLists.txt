cmake_minimum_required(VERSION 3.20)

project(HelloGithubAction)

find_package(SDL2 REQUIRED)

add_executable(main.out src/main.cpp)
target_link_libraries(main.out PUBLIC SDL2::SDL2)