cmake_minimum_required(VERSION 3.9)
project(cnn_demo)

set(CMAKE_CXX_STANDARD 11)

#add_executable(cnn_demo main.cpp cnn01/cnn.h cnn01/cnn.cpp cnn01/cnn01.cpp cnn01/main.cpp)
add_executable(cnn_demo cnn02/CNN.h cnn02/CNN.cpp cnn02/main.cpp )