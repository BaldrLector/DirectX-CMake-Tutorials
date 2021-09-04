add_definitions(-DMBCS)

file(GLOB_RECURSE files *.cpp *.h)
include_directories(../Core)
add_library(DXUT11_Optional ${files})
