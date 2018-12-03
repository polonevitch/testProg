cmake_minimum_required(VERSION 3.0)

project(ferum)

include_directories(${CMAKE_BINARY_DIR}/../../lib)
message (${CMAKE_BINARY_DIR}/../../lib)
link_directories(${CMAKE_BINARY_DIR}/../../lib/build)
add_executable(${PROJECT_NAME} main.cpp)
target_link_libraries(${PROJECT_NAME} hello)

