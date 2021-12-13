cmake_minimum_required(Version 2.4)

project(hello_world)

include_directories(${PROJECT_SOURCE_DIR})
add_executable(app main.cpp foo.cpp)  # Be sure there is exactly one main() function in the source files
