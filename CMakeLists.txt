cmake_minimum_required(VERSION 3.23)
project(dsaa_cpp4)

set(CMAKE_CXX_STANDARD 14)

add_executable(TestVector TestVector.cpp Vector.h)
add_executable(TestList TestList.cpp List.h)
add_executable(TestBinarySearchTree TestBinarySearchTree.cpp BinarySearchTree.h)
add_executable(TestBinaryHeap TestBinaryHeap.cpp BinaryHeap.h)