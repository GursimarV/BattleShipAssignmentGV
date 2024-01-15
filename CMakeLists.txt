cmake_minimum_required(VERSION 3.26)
project(BattleShipAssignmentGV)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(lib)
include_directories(src)
include_directories(tests)

add_executable(BattleShipAssignmentGV
        lib/board.h
        lib/consts.h
        lib/game.h
        src/BattleShipAssignmentGV.cpp
        src/board.cpp
        src/game.cpp
        tests/tests.cpp
        README.md)
