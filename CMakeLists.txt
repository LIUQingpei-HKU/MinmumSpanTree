cmake_minimum_required(VERSION 3.5)
project(05_Implementation_of_Optimized_Prim_Algorithm)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp Edge.h DenseGraph.h SparseGraph.h MinHeap.h IndexMinHeap.h LazyPrimMST.h PrimMST.h ReadGraph.h PrimMST.h KruskalMST.h)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR})
add_executable(05_Implementation_of_Optimized_Prim_Algorithm ${SOURCE_FILES})