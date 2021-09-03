add_executable(Tutorial02 WIN32 Tutorial02.cpp resource.h)
target_link_libraries(
        Tutorial02
        d3d11 d3dcompiler
        d3dx11d d3dx9d dxerr
        dxguid winmm comctl32
)