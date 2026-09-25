cmake_minimum_required(VERSION 3.25)

project(WorkbenchMod VERSION 1.0.0 LANGUAGES CXX)

find_package(Geode REQUIRED)

add_geode_mod(
    yourname.workbench_mod
    VERSION v1.0.0
    CONTAINS_GEODE_FILES
    SOURCES main.cpp
)
