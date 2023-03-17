cmake_minimum_required(VERSION 3.21)
project(FEUP_DA_Project1)

set(CMAKE_CXX_STANDARD 14)

add_executable(FEUP_DA_Project1 main.cpp data_structures/Graph.cpp data_structures/Heap.cpp
        data_structures/Station.cpp data_structures/UFDS.cpp
        data_structures/VertexEdge.cpp data_structures/Database.cpp)
