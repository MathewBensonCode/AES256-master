cmake_minimum_required(VERSION 3.28)

project(AESinCpp CXX)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENTIONS OFF)

add_executable(AesCpp)

target_sources(AesCpp PRIVATE AES256.cpp)
