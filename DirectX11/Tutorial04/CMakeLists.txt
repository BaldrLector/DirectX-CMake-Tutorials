add_executable(Tutorial04 WIN32 Tutorial04.cpp resource.h)
target_link_libraries(
        Tutorial04
        d3d11 d3dcompiler
        d3dx11d d3dx9d dxerr
        dxguid winmm comctl32
)

