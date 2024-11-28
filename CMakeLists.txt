project(OpenVG)
include(CMakeForceCompiler)

set(CMAKE_SYSTEM_NAME Generic)
cmake_minimum_required(VERSION 3.13)

enable_language(ASM)

set(PROJ_DIR ${CMAKE_CURRENT_SOURCE_DIR})

add_subdirectory(vendor/nxp)
