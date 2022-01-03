# Cmake support for FastNoiseLite

project(FastNoiseLite)

add_library(${PROJECT_NAME} INTERFACE)
target_include_directories(${PROJECT_NAME} INTERFACE "Cpp")