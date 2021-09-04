file(GLOB_RECURSE files *.cpp *.h)
include_directories(../Core)
add_library(DXUT_Optional ${files})
