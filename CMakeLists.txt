cmake_minimum_required(VERSION 3.18)


project(untitled2)

set(CMAKE_CXX_STANDARD 23)

# DirectX
include_directories("$ENV{DXSDK_DIR}/Include")
link_directories("$ENV{DXSDK_DIR}/Lib/x64")
message( "DXSDK_DIR:\t" $ENV{DXSDK_DIR} )

add_subdirectory(DirectX11)
