cmake_minimum_required(VERSION 3.10)

project(CmakeDemo)

include_directories("${PROJECT_SOURCE_DIR}/third_part/build-system-lib")
add_subdirectory("${PROJECT_SOURCE_DIR}/third_part")

add_executable(main main.c)

target_link_libraries(main MathLib)
