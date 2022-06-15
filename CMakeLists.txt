cmake_minimum_required(VERSION 3.20)

project(HelloGithubAction)

find_package(SDL2 REQUIRED)

add_executable(main.out src/main.cpp SDL2::SDL2)