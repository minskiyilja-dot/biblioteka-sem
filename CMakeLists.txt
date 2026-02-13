cmake_minimum_required(VERSION 3.10)
project(biblioteka)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDART_REQUIRED ON)
include_directories(include)
add_executable(${biblioteka}
    main.cpp
    src/Class1.cpp
    src/Class2.cpp
    src/Class3.cpp
    include/Class1.h
    include/Class2.h
    include/Class3.h
)