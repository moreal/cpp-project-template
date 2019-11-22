cmake_minimum_required(VERSION 3.12.4)

project(project_name)

set(CXX_STANDARD 17)
file(GLOB SRC_FILES src/*.cc)

include_directories(include)

add_executable(project_name ${SRC_FILES})
