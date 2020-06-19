cmake_minimum_required(VERSION 3.14)
project(ex4_os)

set(CMAKE_CXX_STANDARD 14)

add_executable(ex4_os MemoryConstants.h PhysicalMemory.cpp PhysicalMemory.h SimpleTest.cpp VirtualMemory.cpp VirtualMemory.h)