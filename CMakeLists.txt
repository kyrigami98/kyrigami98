cmake_minimum_required(VERSION 3.14)
project(ProjetMachineLearning)

set(CMAKE_CXX_STANDARD 14)

set(EIGEN_DIR "/home/a2/Documents/5AL/S1/Machine Learning/eigen3.3.7")
include_directories(${EIGEN_DIR})

add_executable(ProjetMachineLearning main.cpp)
target_link_libraries(ProjetMachineLearning ${EIGEN_DIR})