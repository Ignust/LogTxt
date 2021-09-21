cmake_minimum_required(VERSION 3.5.1)

#project(LogTxt LANGUAGES CXX )
project(LogTxt)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_FLAGS "-Wall -pthread")

set(SOURCES
    main.cpp
)

add_executable(LogTxt ${SOURCES})
