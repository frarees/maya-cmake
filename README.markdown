# FindMaya.cmake

## Installation

Include FindMaya.cmake in your user-created CMake module path. If you don't have one, you should. Follow these steps: 

1. Create a `cmake` (or whatever name you like) folder at the same level as your `CMakeLists.txt`. 
2. Open your `CMakeLists.txt` and add a reference to that path (`SET(CMAKE_MODULE_PATH ${CMAKE_CURRENT_SOURCE_DIR}/cmake)`). 

## Usage

`find_package(Maya)` will do. 

## Current state

This module currently works only for a Maya 2012 distribution installed on Mac OS X. It needs to be extensively expanded. See *collaboration*. 

## Collaboration

Collaboration is encouraged thought forks and pull requests. 