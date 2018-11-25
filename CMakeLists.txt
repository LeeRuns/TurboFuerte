# TURBO FUERTE Main Project CMake Script
# Lee Runyon

cmake_minimum_required (VERSION 2.6)
project (Tutorial)
# The version number.
set (Tutorial_VERSION_MAJOR 1)
set (Tutorial_VERSION_MINOR 0)


add_subproject(src)
add_subproject(extern)
