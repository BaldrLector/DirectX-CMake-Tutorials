add_executable(Tutorial05 WIN32 Tutorial05.cpp resource.h)
target_link_libraries(
        Tutorial05
        d3d11 d3dcompiler
        d3dx11d d3dx9d dxerr
        dxguid winmm comctl32
)

