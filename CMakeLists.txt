cmake_minimum_required(VERSION 3.0)
project(clinfo)

include_directories(./include)
link_directories(${CMAKE_CURRENT_SOURCE_DIR}/lib)

add_executable(clinfo src/clinfo.c)

target_link_libraries(clinfo OpenCL)