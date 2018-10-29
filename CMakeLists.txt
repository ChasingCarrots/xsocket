cmake_minimum_required(VERSION 3.5)
project(xsocket)

add_library(xsocket INTERFACE)
target_include_directories(xsocket INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})
target_link_libraries(xsocket INTERFACE wsock32 ws2_32)
