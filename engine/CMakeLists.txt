project(engine)

file(GLOB_RECURSE SRC_FILES src/*.cpp)
include_directories(${CMAKE_SOURCE_DIR}/include)

add_executable(${PROJECT_NAME} ${SRC_FILES})

add_dependencies(${PROJECT_NAME} glm)
target_link_libraries(${PROJECT_NAME} glm)