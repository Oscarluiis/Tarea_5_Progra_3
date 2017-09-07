cmake_minimum_required(VERSION 3.8)
project(EstructuraTarea3_master)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        bin/Debug/Tarea1
        bin/Debug/Tarea2
        bin/Debug/Tarea3
        cmake-build-debug/cmake_install.cmake
        cmake-build-debug/CMakeCache.txt
        cmake-build-debug/EstructuraTarea3_master.cbp
        cmake-build-debug/Makefile
        CMakeLists.txt
        Evaluador.cpp
        Evaluador.h
        main.cpp
        README.md
        Tarea2.depend
        Tarea2.layout
        Tarea3.cbp
        Tarea3.depend
        Tarea3.layout)

add_executable(EstructuraTarea3_master ${SOURCE_FILES})