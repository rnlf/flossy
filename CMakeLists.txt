project(flossy)
cmake_minimum_required(VERSION 3.4)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++14 -g -pedantic -Wall")

add_executable(flossy_test
  flossy_test
)
