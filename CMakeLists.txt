cmake_minimum_required(VERSION 3.17)

project(Journey)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS ON)

set(BUILD_DIR ${CMAKE_SOURCE_DIR}/build/)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${BUILD_DIR}/bin/)
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${BUILD_DIR}/bin/)
set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${BUILD_DIR}/bin/)

add_subdirectory(engine)
add_subdirectory(external/glm)