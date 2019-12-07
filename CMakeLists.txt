cmake_minimum_required(VERSION 3.10)
project(helloAction)
set(CMAKE_CXX_STANDARD 11)
add_executable(helloaction main.cpp)
target_compile_options(helloaction PRIVATE 
--coverage)
target_link_libraries(helloaction PRIVATE
--coverage)