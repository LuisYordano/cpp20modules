cmake_minimum_required (VERSION 2.6)

project (cpp20modules)

add_compile_options(
    -std=c++20 
    -fmodules-ts 
)

# order is important

add_executable(cpp20modules hello.cc cpp20modules.cpp)
