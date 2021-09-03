
add_executable(Tutorial00 WIN32 Tutorial00.cpp resource.h)
target_link_libraries(
        Tutorial00
        d3d11 d3dcompiler
        d3dx11d d3dx9d dxerr
        dxguid winmm comctl32
)