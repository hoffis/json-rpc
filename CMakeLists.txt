CMAKE_MINIMUM_REQUIRED(VERSION 2.8)
PROJECT(json-rpc)
#======================================================================
# Recurse to subdirectories
include_directories(include/)
include_directories(external/RxCpp/Rx/v2/src/)
include_directories(external/json/src/)

add_definitions(-std=c++1y)
add_subdirectory(src)

