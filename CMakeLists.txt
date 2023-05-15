cmake_minimum_required(VERSION 3.26.3)

project("Rog")

set(SOURCE_FILES 
    src/kutuphane.cpp
    src/main.cpp)

set(INCLUDE_FILES 
    include/kutuphane.h)

include_directories(include/)
add_executable(${PROJECT_NAME} ${SOURCE_FILES})
