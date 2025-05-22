cmake_minimum_required(VERSION 3.10)
project(SideViewMirror)

# Add source files
set(SOURCES
    src/Example.cpp
    # Add other source files here
)

add_library(Example ${SOURCES})

# Include directories
include_directories(include)

# Add tests if any
# add_subdirectory(tests)


