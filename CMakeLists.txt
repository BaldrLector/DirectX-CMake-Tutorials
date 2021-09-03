cmake_minimum_required(VERSION 3.18)


project(DirectX11-CMake-Tutorials)

set(CMAKE_CXX_STANDARD 23)
#set(CMAKE_CXX_CLANG_TIDY "clang-tidy;-fix;-fix-errors")
add_compile_definitions(UNICODE _UNICODE)


# DirectX
include_directories("$ENV{DXSDK_DIR}/Include")
link_directories("$ENV{DXSDK_DIR}/Lib/x64")
message("DXSDK_DIR:\t" $ENV{DXSDK_DIR})

add_subdirectory(DirectX11)
