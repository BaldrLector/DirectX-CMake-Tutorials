cmake_minimum_required(VERSION 3.18)


project(DirectX11-CMake-Tutorials)

set(CMAKE_CXX_STANDARD 23)
#add_compile_definitions(UNICODE _UNICODE)
#set(CMAKE_CXX_CLANG_TIDY "clang-tidy;-fix;-fix-errors")
#set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS}  /permissive- /RTC1 /Zc:wchar_t /WX- /Zc:twoPhase-")
#/EHsc /WX /sdl /MP
# DirectX
#include_directories("$ENV{DXSDK_DIR}/Include")
#link_directories("$ENV{DXSDK_DIR}/Lib/x64")
#message("DXSDK_DIR:\t" $ENV{DXSDK_DIR})


add_subdirectory(libs)
add_subdirectory(DirectX11)
