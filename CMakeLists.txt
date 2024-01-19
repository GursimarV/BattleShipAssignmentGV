cmake_minimum_required(VERSION 3.26)
project(BattleShipAssignmentGV)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(cmake-build-debug/lib)
include_directories(cmake-build-debug/src)
include_directories(cmake-build-debug/tests)

add_executable(BattleShipAssignmentGV
        cmake-build-debug/lib/board.h
        cmake-build-debug/lib/consts.h
        cmake-build-debug/lib/game.h
        cmake-build-debug/src/BattleShipAssignmentGV.cpp
        cmake-build-debug/src/board.cpp
        cmake-build-debug/src/game.cpp
        cmake-build-debug/tests/tests.cpp
        README.md)
