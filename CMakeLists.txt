cmake_minimum_required(VERSION 4.4.5)

project(Hydroviewer LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 26)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(
	antares
	src/main.cpp
)

target_include_directories(antares PRIVATE include)
