cmake_minimum_required(VERSION 3.28)

project(AESinCpp CXX)

add_executable(AesCpp)

target_sources(AesCpp PRIVATE AES256-master/AES256.cpp)
