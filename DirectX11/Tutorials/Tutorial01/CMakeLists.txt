add_executable(Tutorial01 WIN32 Tutorial01.cpp resource.h)
target_link_libraries(
        Tutorial01
        d3d11 d3dcompiler
        d3dx11d d3dx9d dxerr
        dxguid winmm comctl32
)