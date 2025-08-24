cmake_minimum_required(VERSION 3.16)
project(sword-generator VERSION 0.1.0 LANGUAGES CXX)

# Use modern C++
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Include directory for headers
include_directories(${CMAKE_SOURCE_DIR}/include)

# Main executable
add_executable(sword-generator src/main.cpp)
